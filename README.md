This is a starter template for [Learn Next.js](https://nextjs.org/learn).

### Getting ready for Azure

Following the docs [here](https://learn.microsoft.com/en-us/azure/static-web-apps/deploy-nextjs-hybrid) you can get your app ready for deployment to Azure.

You won't have enough permissions to authorize the Static Web App to create the github action for you, but you can use the one in this repository as a template. Just make sure to rename the secret variable names to something more suitable for your application. This means that in order to create the Azure Static Web App you have to select "Other" when selecting the source for your application.

It is possible to set secrets in a repository that you have write access to using the [Github CLI](https://cli.github.com/) Commands should be executing from the folder that your repository (`.git` folder) is in. We are mainly interested in `gh secret set <secret_name>` Using this you should be able to set the deployment token (that you can get from the Static Web App overview in Azure)

If you need any help please don't hesitate to contact me at [nielsw@delta-n.nl](mailto:nielsw@delta-n.nl)
