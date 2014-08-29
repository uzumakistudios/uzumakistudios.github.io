# Uzumaki Studios Web page 

http://uzumakistudios.com

# Cloning this repos

First of all, clone this repos:

    git clone https://github.com/uzumakistudios/uzumakistudios.github.io
    cd uzumakistudios.github.io

# Creating a new blog post

Before start editing this repos, update it:

    git pull

Create a new file to your post named `_posts/yyyy-mm-dd-title-of-post.md` with the following syntax:

   ---
   layout: post
   title: Title of post
   ---
   
   Foo bar.

To commit and push your blog post:

   git add --all
   git commit -am "My new post"
   git push origin master

# Editing a page

It´s the same of editing a blog post, but instead of editing a file in `_posts/`, edit the page's index file, like `about/index.html`.

# Setting up Jekyll locally

If you want to preview the generated blog locally, install Jekyll following these instructions [here](https://help.github.com/articles/using-jekyll-with-pages#installing-jekyll).

To preview locally:

   jekyll serve

Then access `http://localhost:400`.

