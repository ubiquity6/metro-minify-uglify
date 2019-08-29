NOTE: This fork is no longer used as of [Display PR-7020](https://github.com/ubiquity6/ubiquity/pull/7020)

# metro-minify-uglify
fork of minify-uglify for metro with custom parameters.

This repo hosts a compiled version of metro-minify-uglify

Changes:
The uglify.minify function call's second argument is a config object. We have removed two key/value pairs:
```jsx
keep_classnames: true,
keep_fnames: true,
```
