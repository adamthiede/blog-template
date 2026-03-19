# Blog Template

A basic personal website template for markdown posts.

To demo yourself, install `python3` and `discount` which provides the `markdown` binary. Your OS should have these in its package repositories. Run `./build.py`. It will generate the files in `posts` from the markdown in `source`.

To make your own website you can easily deploy this to github pages. It's zero-cost free infrastructure. If you want a nice domain (youraccount.github.io) you must name the repo "youraccount.github.io" when forking.

## Customization

The templates directory contains a header and footer for each post, and for the main page. It's just HTML. There is one sample post in the `source` directory.

Pages are sorted in reverse order - biggest number or letter goes at the top of the list. Plan accordingly.

### Github

In your github repo, after forking this one, go to "settings" -> "pages", and for the deploy model choose "Github Actions".

### Gitlab

Just fork the repo and the action will run and do the rest.

## License

Python code is AGPL.
