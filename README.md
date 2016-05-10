[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

# Why?

This will fail to deploy since there is a dependency specified that does not exist.

You'll see the following error on deploy.azure.com:

![deploy failure](./img/failure1.png)

Which is a result of the failure on portal.azure.com:

![portal failure](./img/failure2.png)

Which is a result of the npm install failure:

![npm failure](./img/failure3.png)