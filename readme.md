## shimopage

https://kuroponzu.github.io/

## themes

[soho](https://github.com/alexandrevicenzi/soho)
## deploy

### local
 - `brew install hugo`
 - `cd themes/`
 - `git submodule add https://github.com/alexandrevicenzi/soho.git`
 - `git submodule update --init`
 - `hugo server`

### production

 - Create a branch from master branch
 - Create PR
 - Marge to master branch
 - Auto deploy production environment with github_actions
