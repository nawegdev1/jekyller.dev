# jekyller-webclient
Basic JavaScript library for integrating inline content editing with the backend services provided by jekyller-services

### My Starting Web Process
When I am using Jekyller for a new site, I typically do the following, which keeps things organized.

1. Create a new email account.  I typically use the free gmail.com for this.  This will be used for 
other services and can be used as an admin type account for the site.
2. Create a new github.com account, registering with the new email account setup.
3. Create a new directory for the site in development environment.  I typically name it the domain name of the site.
4. Download the Jekyller-Services repo and unzip it into a child directory called services.
5. Download the Jekyller-Webclient repo and unzip it into a child directory named after the domain name of the site.
6. Create the website repo in the new github.com account which will be the primary repo for this account.
7. Clone the repo into a child directory of the main project.  Use similar syntax to _git clone https://username:password@github.com/username/repository.git_ in order to associate the local repo with the github.com repo using the new github account.
7. Setup the git [user.name](https://help.github.com/articles/setting-your-username-in-git/) and [user.email](https://help.github.com/articles/setting-your-commit-email-address-in-git/) within the new website child directory using the git documentation that outlines this.
9. Edit the website project _config.yml properties of the Jekyller based site.  It is important to setup the url option to the new domain name.
10. Use the config options of the repo in github.com to setup the github pages account.
