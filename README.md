# Atom configuration

## Installing on a new system

Backup old atom directory:

`mv ~/.atom ~/.atom_bak`

Then grab the .atom folder from github:

`git clone git@github.com:bwsprague/dotatom.git ~/.atom`

and install the packages by running:

`apm install --packages-file package-list.txt`

## Updating the package list

If you install new packages, you should run

`apm list --installed --bare > ~/.atom/package-list.txt`

and push the changes to github.

## Notes

Currently at least one package requires [node-gyp](https://github.com/nodejs/node-gyp#installation) to be installed.
