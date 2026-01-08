Minimal portfolio website forked from [gouravkhunger](https://github.com/gouravkhunger/portfolio) (thanks!) 

See README in link above for more information regarding the installation and usage of the template

## How to deploy to github pages
Once all the changes have been tested:

1. Create in local the `_site` folder executing `bundle exec jekyll serve`.
2. Copy the contents to the hosting repository (`robertomzc.github.io`)
3. Push to Github
4. Go back to the original (`portfolio`) repository and merge the branch into `master`. This will trigger the `gh-pages` deployment and show the site at the `.github.io` address.

### More in detail
The site is hosted in the hosting repository, whereas the original repository is used to git track the portfolio code. The original repository triggers the deployment, but the contents of the deployed website are hosted in the hosting repository


