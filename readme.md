# Personal website using hugo-apero

My personal website was built using Bookdown with lots of help from [Allison Hill](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/).

### Workflow

`blogdown::serve_site()` will render the page on localhost, to see any new changes in real time.

`blogdown::build_site()` when done making changes to rebuild the site, which will change the public folder.

Any changes -> push to Github and Netlify will automatically deploy it.
