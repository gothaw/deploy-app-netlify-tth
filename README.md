# deploy-app-netlify-tth

Course Directory application from Team TreeHouse course. Testing how to deploy an app to Netlify.

To configure routing in the app include `_redirects` file in a build folder with:

````
/*    /index.html   200
````
This will always serve index.html instead of giving 404.

Resources:

- [Netlify](https://www.netlify.com)
- [Netlify CLI](https://docs.netlify.com/cli/get-started/)
- [Redirects](https://docs.netlify.com/routing/redirects/)
- [Custom Domains](https://docs.netlify.com/domains-https/custom-domains/)
- [Continous Deployment](https://docs.netlify.com/configure-builds/get-started/)