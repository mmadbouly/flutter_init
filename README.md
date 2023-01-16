# git stuff
>[git cheatsheet](https://www.codingforentrepreneurs.com/blog/setup-git-github-repo/)

> git push -u origin master
- needs the new login method, using personal access token:
-- username will be mmadbouly and 
-- password will be the personal access token

### Merge Remote with Local when changes happens to one of them or on both
- The scenario:
-- changes to Readme.md file on the web interface of the repo (on github)
-- changes to local repo by creating  a new flutter project-app
- The How To

-- `git config pull.rebase false` # merge (the default strategy)
-- `git pull`
-- `git push`



# flutter_init
following the [official page](https://docs.flutter.dev/get-started/install) for setup, test drive and tutorials
### issues faced when running and debugging from VSC
- install cmake

-- from ubuntu software center
- install ninja 

-- `sudo apt-get install ninja-build`
- install clang

-- `sudo apt install clang`
