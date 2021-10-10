# netlifysite
Deploy Serverless CMS using Netlify

This is the repo that uses HUGO to deploy static html files that are hosted on https://github.com/mokdarren/mokdarren.github.io

How to update:
1. `git clone https://github.com/mokdarren/netlifysite.git` : clone repo containing hugo files
2. `git submodule init` : initialise submodules (themes)
3. `git submodule update` : update submodules
4. `hugo server -w` : deploy html files locally
5. perform changes in .md files
6. `hugo -d ../mokdarren.github.io/` deploy html to other file
7. `cd ../mokdarren.github.io`
8. `git add .`
9. `git push origin master` push changes to github repo hosting site
