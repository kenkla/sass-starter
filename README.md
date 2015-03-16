# Sass Project Starter for Compass

## Overview
This repo contains a starting point for projects using Sass and Compass to generate CSS3. It contains an HTML5 page template and a corresponding Sass file for each section in the template.  

## Usage
1. Inside your new project folder, create a new Sass project using Compass
```ubuntu
compass create {your-project}
```
2. Tell Compass to look for changes to your Sass and compile them to CSS.
```ubuntu
compass watch
```
3. Clone the repo into your new project.

### Modify the Layout
To add a section, add the markup to the HTML template, create a corresponding Sass file for it in the sass/layout folder, and use the @import command in the _layout.sass file to load it into your Sass.

To remove a section, just remove the markup from the HTML template, remove the corresponding Sass file in the sass/layout folder and remove the @import command from the _layout.sass.

