# To install Node in AWS Linux

## To set up Node.js on your Linux instance

1. Connect to your Linux instance as ec2-user using SSH.

2. Install node version manager (nvm) by typing the following at the command line.

``` curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash```

3. Activate nvm by typing the following at the command line.

```. ~/.nvm/nvm.sh```

4. Use nvm to install the desire version.

To check the version type
```nvm list-remote```

5. to install the specific version, do like this  
   ```nvm install 16```

   [Amazon Linux 2 does not currently support the current LTS release (version 18.x) of Node.js. Use Node.js version 16.x with the following command instead.]

6. To check the version of node, type

``` node -e "console.log('Running Node.js ' + process.version)"```
