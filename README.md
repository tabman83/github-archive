# github-archive

[![NPM](https://nodei.co/npm/github-archive.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/github-archive)

[![Build Status](https://travis-ci.org/tabman83/github-archive.svg?branch=master)](https://travis-ci.org/tabman83/github-archive) 

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

> github-archive is a simple tool that backs up every repository and branch for a specified user.

You will never be missing again your Dublin Bus ride! This web application shows the due time for your next ride a warns you when time is running out.
The backend will keep an eye for you at the expected times at your preferred stop. Any update will be instantly pushed to your screen!

## Use

Run ```github-archive``` followed by the auth token of the user and the account name (or organizational account name).

For your convenience you can create a specific backup user (say BackupAgent) who is allowed to browse any repository you want to back up.

To get an auth token for this user, logs into its GitHub account, go into Settings, Personal access tokens, then Generate new token. Please store your token safely.

## Example

```
github-archive 5a1a2393ca99685410fcd71e6e915232cb4fe21a YourOrganizationName
```

Everything will be backed up under the ```data``` folder.

## Why backup a GitHub repository

In case something happens to GitHub. More generally because keeping your data in the cloud and relying on the cloud to back it up is foolish.

## Author

github-archive was written by Antonino Parisi tabman83@gmail.com

It is made possible thanks to:
github-api: 
* Michael Aufreiter's github-api library (https://github.com/michael/github)
* GitHub, for providing an API exposing this data.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Antonino Parisi](https://github.com/tabman83) has waived all copyright and related or neighboring rights to this work.
