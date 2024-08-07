---
title: GitBuilds
description: An introduction to upcoming versions of Dodo-Bot!
---
GitBuilds are development versions of Dodo-Bot hosted on Github that isn't ready to be considered as "stable" release. While usually new features or changes are introduced, there may be also bugs considering that they're unfinished builds which is why it's not recommended for public use as they're only meant for testing.

# Methods of testing
There're 3 ways of testing GitBuilds. These are being:
* Downloading a released Pre-release build through [releases](https://github.com/DodoGames7/Dodo-Bot/releases)
* Downloading the latest incomplete Pre-release build of a upcoming GitBuilds build
* Inviting [Official Dodo-Bot Alpha bot](https://discord.com/api/oauth2/authorize?client_id=970481494797738016&scope=bot+applications.commands&permissions=36032) into your server to directly test the latest Pre-release builds


For now, The installation method will focus on downloading the latest incomplete builds but feel free to use the other methods listed above!

# Installing
GitBuilds are obtainable through the branch [gitbuilds](https://github.com/dodogames7/Dodo-Bot/tree/gitbuilds).

This guide will use local hosting for testing purposes for now but you can host the builds on any hosting such as Replit if needed for reasons.

Obtaining the build using Git:
```js
// installing v2 pre-release build
git clone https://github.com/dodogames7/Dodo-Bot -b gitbuilds

// installing rebase pre-release build
git clone https://github.com/dodogames7/Dodo-Bot -b gitbuilds-rebase
```
:::tip[Don't have Git installed?]
You can also directly download the latest dev build [here](https://github.com/DodoGames7/Dodo-Bot/archive/refs/heads/gitbuilds.zip).
:::

This should create a folder called `Dodo-Bot`

Now setting up the latest build should be as easy as:
```js
cd Dodo-Bot && npm install
```

To setup the bot, go to `config.json` and configure the available setup options for the bot.

Once you're done, open the terminal and run `node .` and the bot should start. Have fun with testing!


# Updating the build
If you have git installed then it should be as easier as running a command in the terminal. It is also recommended to regular use `npm install` command as well as GitBuilds builds may sometimes update aoi.js development builds to latest. This will only work for fresh installations that didn't have the `config.json` file touched.

Enter the following command inside the directory that contains the code:
```js
git pull && npm install
```

This will update your current install to the latest development build by pulling out the latest files from the branch including updating the packages to their latest versions.

:::tip[Not using Git?]
You may redownload the zip to update to the latest build as there's currently no method to update for non git OSes.
:::
