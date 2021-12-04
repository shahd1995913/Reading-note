# Deploying Your Next.js App
## Download Starter Code
- [x] npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/basics-final"

## == Push to GitHub ==
### Before  deploy,  push our Next.js app to GitHub .
### This will make deployment easier.
### On  personal GitHub account, create a new repository called nextjs-blog.
### The repository can be public or private. 
### You do not need to initialize it with a README or other files.
### If you haven’t initialized the git repository locally for your Next.js app, do so now.
### Push the Next.js app to  GitHub repository.
### To push to GitHub, you can run the following commands (replace <username> with your GitHub username)
- [x] git remote add origin https://github.com/<username>/nextjs-blog.git
- [x] git push -u origin main
### == Deploy to Vercel ==
### The easiest way to deploy Next.js to production is to use the Vercel platform developed by the creators of Next.js.

### Vercel is a serverless platform for static and hybrid applications built to integrate with your headless content, commerce, or database.
###  make it easy for frontend teams to develop, preview, and ship delightful user experiences, where performance is the default. 

## === Create a Vercel Account===
### 1. First, go to https://vercel.com/signup to create a Vercel account.
### 2. Choose Continue with GitHub and go through the sign up process.

### 3. Import your nextjs-blog repository
### 4. Once you’re signed up, import your nextjs-blog repository on Vercel. You can do so from here: https://vercel.com/import/git.
### 5.  need to Install Vercel for GitHub. You can give it access to All Repositories.
### 6.  Once  installed Vercel, import nextjs-blog.
## Vercel automatically detects that you have a Next.js app and chooses optimal build settings for you.

- [x] Project Name
- [x] Root Directory
- [x] Build Command
- [x] Output Directory
- [x] Development Command

## Vercel is made by the creators of Next.js and has first-class support for Next.js.
### When you deploy your Next.js app to Vercel, the following happens by default:

1. Pages that use Static Generation and assets (JS, CSS, images, fonts, etc) will automatically be served from the Vercel Edge Network, which is blazingly fast.
2. Pages that use Server-Side Rendering and API routes will automatically become isolated Serverless Functions. This allows page rendering and API requests to scale infinitely.

## Vercel has many more features, such as:

1. Custom Domains: 
- Once deployed on Vercel, assign a custom domain to your Next.js app. 
2. Environment Variables: 
-  can also set environment variables on Vercel. You can then use those environment variables in Next.js app.
3. Automatic HTTPS:
-  HTTPS is enabled by default (including custom domains) and doesn't require extra configuration.