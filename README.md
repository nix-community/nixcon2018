<a href="https://travis-ci.org/zimbatm/nixcon2018"><img src="https://travis-ci.org/zimbatm/nixcon2018.svg?branch=master"></a>

# Website for NixCon 2018

copied from https://github.com/cko/nixcon2017

## Build

The site is build with [Hakyll](https://jaspervdj.be/hakyll/)

    ghc --make site.hs
    site build
    site server

### Build with nix

    nix-build

## Travis Deployment

Go to GitHub.com -> Settings -> Applications -> Personal Access Tokens — > Create new token, and copy it to your clipboard
` travis encrypt -r zimbatm/nixcon2018 GH_TOKEN=[your token]`
