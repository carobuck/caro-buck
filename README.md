This is a cheatsheet of useful commands for building my site, mostly for my own benefit and memory. 

Helpful resources I've used along the way:

* Thomas Mock's [blog posts](https://themockup.blog/posts/2020-08-01-building-a-blog-with-distill/)
* Distill for RMarkdown [documentation](https://rstudio.github.io/distill/)

Commands/helpful tips:

* Use distill::create_post("title of post") to create a new post + hierarchy of folders/supporting files for the post
* When it comes time to publish (once you're connected to git + Netlify), knit the index.Rmd file (which knits all the _posts) and about.Rmd file, then git commit/push all updates and Netlify site should be updated automatically. 