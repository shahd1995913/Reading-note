# API Deployment
## Configuring Django Settings: Best Practices
### Different environments. 
- Usually, you have several environments: local, dev, ci, qa, staging, production, etc. 
- Each environment can have its own specific settings (for example: DEBUG = True, more verbose logging, additional apps, some mocked data, etc).
-  You need an approach that allows you to keep all these Django setting configurations.

### Sensitive data.
-  You have SECRET_KEY in each Django project.
-  On top of this there can be DB passwords and tokens for third-party APIs like Amazon or Twitter.
-  This data cannot be stored in VCS.
## How Does SSH Work
## What is SSH
### SSH, or Secure Shell, is a remote administration protocol that allows users to control and modify their remote servers over the Internet. 
- The service was created as a secure replacement for the unencrypted Telnet and uses cryptographic techniques to ensure that all communication to and from the remote server happens in an encrypted manner.
-  It provides a mechanism for authenticating a remote user, transferring inputs from the client to the host, and relaying the output back to the client.
## Authenticating the User
- The final stage before the user is granted access to the server is authenticating his/her credentials. 
- For this, most SSH users use a password. The user is asked to enter the username, followed by the password. 
- These credentials securely pass through the symmetrically encrypted tunnel,
- so there is no chance of them being captured by a third party.

- Although passwords are encrypted, it is still not recommended to use passwords for secure connections. 
- This is because many bots can simply brute force easy or default passwords and gain access to your account.
-  Instead, the recommended alternative is SSH Key Pairs.

