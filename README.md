# My Genesis Developer's Starter Child Theme

Genesis by [Studiopress](http://www.studiopress.com/) is my framework of choice when building WordPress themes for small businesses and non-profits with smaller budgets. Why? Because it is: 

- developer friendly
- very easy to customize once you get the hang of the hooks and filters
- lean
- well coded
- fast
- secure
- SEO enabled with built-in microdata (schema.org)
- accessible
- well maintained by the highly competent team @ Studiopress 

This is a developer friendly starter child theme for the Genesis framework, which includes a modular architecture, Sass, Gulp, Bourbon, Neat and Composer. Find the whole theme on [GitHub](https://github.com/webjen/my-genesis-starter-theme).

Note: This is a starter theme that is meant to be extended and customized. It is based loosely on the Genesis Sample child theme.

## Features

This theme includes the following features:

- Modular programming language
- Configuration based architechture
- Modular CSS via [Sass](http://sass-lang.com/)
- Task runner uses [Gulp](http://gulpjs.com/)
- Uses [Bourbon](http://bourbon.io/) and [Neat](http://neat.bourbon.io/)

## Dependencies

This child theme requires the following frameworks

- [WordPress](https://wordpress.org)
- [The Genesis Framework](http://my.studiopress.com/themes/genesis/)

## Customization

Make your changes in the Sass-files located under the theme folder 'assets/sass' and run 'gulp styles' in terminal.

If you want to automate this you can set a task in the terminal for it. Just go to wp-content/themes/your-theme-folder and run the command 'gulp watch'. It will now watch for changes in the Sass-files and generate the CSS whenever you save changes to a Sass-file. 

You can stop the watch with CTRL + C.

Should you attempt to save a Sass-file that has errors in it you will get an error message and the watch will be discontinued. If that happens you can just start the watch again with 'gulp watch', fix the errors (see the terminal output) and save the file.

### Configuration

I have set up the Sass-folders in a way that makes most sense to me, but feel free to rename and/or rearrange them in a way that works for you. Just remember to update the *index.scss* files in each folder, and the *style.scss* file in the theme root accordingly, otherwise the theme will break.

## Installation

1. Download or clone from GitHub: https://github.com/webjen/my-genesis-starter-theme
2. Run 'npm install' to install all components.

## Contributors

All feedback, bug reports, and pull requests are welcome.
