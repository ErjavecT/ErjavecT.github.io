# Tyler Erjavec's Homepage

## Editing instructions
Full instructions for this theme can be found [here](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).
I will try to summarize some basic instructions when I have time.

Add new webpages in either Markdown (``.md``) or HTML (``.html``) to the ``_pages/`` folder. For either case, at the very top add
```
---
permalink: /myurl/
title: "My Page Title"
---
```
as this will allow for you to link the page in the navigation bar.
To link the page in the navigation bar, edit ``_data/navigation.yml`` and add under ``main``
```
- title: "My Page Title"
  url: /myurl/
```



## Local build instructions
First, download the theme from GitHub:
```bash
git clone git@github.com:ErjavecT/ErjavecT.github.io.git
cd ErjavecT.github.io.git
```

### First time running
When first downloading the code, run 
```bash
bundle install
```
to install the necessary gems for the project. You may need to run it with ``sudo`` permissions.

### Create local server for debugging
To create a local server, run
```bash
bundle exec jekyll serve
```

To view the website, in a browser go to the url ``http://127.0.0.1:4000``.