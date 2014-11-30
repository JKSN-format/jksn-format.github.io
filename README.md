JKSN-format.github.io
=====================

This is the JKSN format web repository. To contribute, just do it the regular
way—issues and pull requests are welcome.

This site uses the [Jekyll](http://jekyllrb.com/docs/home/) CMS to build,
and [GitHub pages](https://github.io) provides us with such environment.

Directory Tree
--------------

- `_layouts/` Template files.
- `_includes/` HTML snippets used to include pages.
- `assets/` JS, CSS and images.
  - `JKSN/` a git submodule.
- `about/` About this site, may contain TODOs.

File Format
-----------

All files are markdown files with a `.md` file extension. These files will be
converted to `.html` files if they contain the following header fields:

    ---
    published: true
    layout: bookpage
    weight: 60
    category: Help
    title: A Certain Title - JKSN Help
    ---


Build offline
-------------

Install Jekyll:

    sudo gem install jekyll

Start the server:

    jekyll serve --watch
    
Now browse [localhost:4000](http://localhost:4000)
