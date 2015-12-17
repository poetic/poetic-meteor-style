# Poetic Meteor Style

This package supplies an `eslint` configuration for working on Meteor apps.
It likes long walks on the beach, ES6 functionality (including modules!),
React components (now in JSX!), and most anything else needed to develop in
Meteor.

It uses [AirBnB's configuration](https://github.com/airbnb/javascript) as a
 base, and extends it with some Meteor-specific options.

## Installation
Run the following command to install the bits of `eslint` that we need:

`npm install -g eslint-config-airbnb eslint-plugin-react eslint`

Then, add the `.eslintrc` and `.eslintignore` files to your app directory.

## Usage
To run `eslint` from the command line, try this from your app directory:

`eslint --ext '.js, .jsx' .`

If you would like to use `eslint` in `vim`, install Syntastic and add the
following line to your `.vimrc`:

`let g:syntastic_javascript_checkers=['eslint']`

*Be sure to remove any other lines that set `syntastic_javascript_checkers`,
 if they exist.*
