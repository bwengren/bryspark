# BrySpark v.1.0.0

This project contains a style guide and proof of concept for this upcoming opportunity.

## Requirements

An open mind.

This was the first pass at cleaning up the UI for the existing application(s), brining an updated look and feel to the overall platform. It was also the first pass at realigning the menu structure, trying to minimize the amount of "clicks it takes the get the center of a Tootsie Roll pop".

[Demo](http://www.soada.org/bryspark)

## Quickstart

```bash
git clone git@github.com:bwengren/bryspark.git
```

## Directory Structure

  - `scss/app.scss`
  	- The app SCSS file. This compiles into app.css and app.min.css
  	- **IMPORTANT** Without the component SCSS directory (which is not included in this repo), you will not be able to compile the CSS.
  - `scss/_icons.scss`
  	- Intializes the custom SVG icon fonts for the app (because we don't uses images or sprites).
  - `scss/_settings.scss`
  	- This is where all the cool stuff happens, namely overrides and custom styles.

