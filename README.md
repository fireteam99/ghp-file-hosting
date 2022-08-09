# ghp-file-hosting

## How to Host Static Files

1. Create a github respository
2. Add your desired static files to the respository
3. Create a dummy `index.html` file
4. Enable github pages by going to your repository's "Settings" > "Pages"
5. Make sure "Source" says "Deploy from a branch" and "Branch" is either "main" or "master" and the folder is "/(root)"
6. You should now be able to access a static resource at `https://{your github username}.github.io}/{repository name}/{path to resource}`
7. You can configure a custom domain in the "Custom domain" section right under "Build and deployment": [more info](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
