# ReadMe: Notes to self for maintaining the site

## Quick reminders: 

- 'docs' is the publishing source of the site
    - Any md file here will appear as a page on the site
- '_posts' contains posts 

## Testing the site locally: 

[See here for detailed instructions](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

- Navigate to publishing source
- run 'bundle install' 
- run 'bundle exec jekyll serve'
- go to http://localhost:4000


## Deploying other repos to the site (e.g. publishing a personal project as a webpage):

- Create a separate repository for that project (e.g. jsFocus contains a jsPsych implementation of a browser-based focus task)
- Go to the Github browser location for that repo. 
- Go to settings -> Pages (on the left) -> Build and Deployment
- Source: Deploy from a branch
- Choose the appropriate branch and Save
- After a few minutes, the repo should be published at site.github.io/repo_name

## Other resources: 

- I set this up following [this link](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#prerequisites)




