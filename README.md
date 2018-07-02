<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250" align="right">

# Node Version Fix

Having problems with your current version of Node? Getting some funky errors? Well look no further because this guide will get you set up with a different version of Node.

If you are using a Windows machine, download [git-bash](https://git-scm.com/download/win) before proceeding.

## Step 1
If you have already installed the latest version of Node at [nodejs.org](https://www.nodejs.org), then go ahead and skip to step two. If not, download the latest stable release of Node.

## Step 2
Crack open your terminal or git-bash and navigate to your home/root directory. Just like NPM, Node also has a version manager, meet NPM's cousin, NVM. Type/copy & paste this into your terminal:
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.4/install.sh | bash
```

This will install NVM on your machine.

Once the installation of NVM is complete, type/copy & paste both of these lines into your terminal:
```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh"
```
This will allow you to use NVM to easily install and switch between versions of Node!

Just to ensure NVM properly installed, type this into your terminal ```command -v nvm```.

As long as you see ```nvm``` listed below your command, you are in good shape.

## Step 3
Now this is where the magic happens! Type out ```nvm install 5.3``` to install version 5.3.
Now type out ```nvm use 5.3``` to use our newly downloaded version.

Type ```node -v``` into the terminal to verify installation of the correct version of Node.

You should now see ```v5.3``` in your terminal.

Happy coding!

## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2017. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<p align="center">
<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250">
</p>
