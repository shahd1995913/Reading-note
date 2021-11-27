# Permissions & Postgresql
## Authentication or identification by itself is not usually sufficient to gain access to information or code. For that, the entity requesting access must have authorization.

- [x] Together with authentication and throttling, permissions determine whether a request should be granted or denied access.
- [x] The simplest style of permission would be to allow access to any authenticated user, and deny access to any unauthenticated user. This corresponds to the IsAuthenticated class in REST framework.

## How permissions are determined
- [x] Permissions in REST framework are always defined as a list of permission classes.
- [x] Before running the main body of the view each permission in the list is checked. 
- [x]  If any permission check fails an exceptions.PermissionDenied or exceptions.
- [x] NotAuthenticated exception will be raised, and the main body of the view will not run.
### Object level permissions
- [x]  REST framework permissions also support object-level permissioning. 
- [x]  Object level permissions are used to determine if a user should be allowed to act on a particular object, which will typically be a model instance.
- [x] 
### Limitations of object level permissions
- [x]  For performance reasons the generic views will not automatically apply object level permissions to each instance in a queryset when returning a list of objects.

## API Reference
1. AllowAny
- The AllowAny permission class will allow unrestricted access, regardless of if the request was authenticated or unauthenticated.

2. IsAuthenticated
- The IsAuthenticated permission class will deny permission to any unauthenticated user, and allow permission otherwise.


3. IsAdminUser
- The IsAdminUser permission class will deny permission to any user, unless user.is_staff is True in which case permission will be allowed.



4. IsAuthenticatedOrReadOnly
- The IsAuthenticatedOrReadOnly will allow authenticated users to perform any request. Requests for unauthorised users will only be permitted if the request method is one of the "safe" methods; GET, HEAD or OPTIONS.


5. DjangoModelPermissions
- This permission class ties into Django's standard django.contrib.auth model permissions. 
- This permission must only be applied to views that have a .queryset property or get_queryset() method.
-  Authorization will only be granted if the user is authenticated and has the relevant model permissions assigned.

6. DjangoModelPermissionsOrAnonReadOnly
- Similar to DjangoModelPermissions, but also allows unauthenticated users to have read-only access to the API.

7. DjangoObjectPermissions
- This permission class ties into Django's standard object permissions framework that allows per-object permissions on models. 
- In order to use this permission class, you'll also need to add a permission backend that supports object-level permissions, such as django-guardian.

