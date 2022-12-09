# Template for a student recipe site

## Usage

This is a template set up for students to begin their own web site. The template is created by Chris Jennings and is based on various Jekyll themes.

`Jekyll` is a system for building and editing static web sites; meaning that it does not need a database for the content. Content can be added with a simple text language called `Markdown`. You can explore and learn **Markdown** here:

https://commonmark.org/help/tutorial/

## Configure

Open `_config.yml` in a text editor to change some settings.


### Site configuration
Configure as your own website in `_config.yml`:

```YAML
  url: "https://username.github.io"
```

Change these variables in `_config.yml`:

```yml
title: Your recipe collection # the all important name of your recipe collection
recipemenu: false # change to true and a menu of all recipes will appear on each recipe page
favicon: uploads/favicon.ico # you can upload your own icon
recipe_bookcover: /uploads/bookcover.jpg #this is a placeholder that you can replace with your own cover image
# change the following to your name or site name for the footer text
footer_text:
  "Copyright 2020 My name"
```

## Prose

We are going to use prose.io to edit the recipes online. Once you have your site setup on github, go to prose.io and allow access to your repository by signing into GitHub. Then you can make edits.
