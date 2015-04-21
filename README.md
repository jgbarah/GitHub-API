# GitHub-API
Learning to use the GitHub-API


I'm using [Github.js](https://github.com/michael/github), which in its own words "provides a minimal higher-level wrapper around [git's plumbing commands](http://git-scm.com/book/en/Git-Internals-Plumbing-and-Porcelain), exposing an API for manipulating GitHub repositories on the file level".

## Creating a token

Follow instructions for [creating an access token for command-line use](https://help.github.com/articles/creating-an-access-token-for-command-line-use/).


## Grab the Github.js library

'''
wget https://raw.githubusercontent.com/michael/github/master/github.js
'''


## Setting up GitHub

* Register a OAuth application with GitHub. For homepage url, I use http://jgbarah.github.io/GitHub-API, for auth callback I use https://auth-server.herokuapp.com/proxy
* Save the data (refernce, domain, client_id, client_secret) with a OAuth proxy. I use https://auth-server.herokuapp.com/