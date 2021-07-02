# Juncture User Guide

This User Guide provides basic information for getting started with Juncture.  More comprehensive documentation can be found at https://juncture-digital.org/docs.

## Overview

### What is Juncture?

Juncture provides an easy way to create interactive web pages (and full web sites) using plain text files that can be edited in a web browser.  Formatting the text and adding visualizations is accomplished using two types of simple text annotation.
- Markdown - 
- Visual essay tags - 

The visual essay tags create visualizatons that use a number of powerful technologies, including:
- IIIF (International Image Interoperability Framework) - 
- Interative maps - 
- LOD (Linked Open Data) -

### What is Github and how does Juncture use it?

### Markdown


## Quick start

- [Create a new Juncture site](#create)
- [Add content to your new site](#adding-content)
- [Customize your site](#customizing)
- [Hosting your site](#hosting)
- [Other](#other)

## Create a new Juncture site
<param id="create">

To create a new Juncture site:
1. First, make a copy of Juncture Github repository in your personal Github repository.  This process is also called _Forking_ a repository and is accomplished by clicking the `Fork` button located at the top of [the main Juncture repository](https://github.com/JSTOR-Labs/juncture-site).
2. After the Juncture repository has been copied (forked), configure the hosting option.  For an initial hosting configuration the standard Github hosting option (_Github Pages_) is used.  Adding a custom domain is supported but is not necessary to get started.

After the site has been created and configured for hosting, you can begin customizing it by adding new content (including a new home page) and configuring the site appearance (like the banner image and menu navigation options)

## Adding content
<param id="adding-content">

### Adding a new home page

### Adding a simple text page

### Adding a visual essay page

```html
    <param ve-config title="Sample Visual Essay" layout="vertical">

    # Sample Visual Essay

    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    <param ve-image url="">
```

## Customizing the site
<param id="customizing">

### Changing the name of your site

### Setting options in the site config

### Defining custom styles

## Configuring the site for Github hosting
<param id="hosting">

### Using custom domain for the site

## Updating the site software version

The Juncture code base is under active development and a forked site can easily be updated to use the latest software version.
