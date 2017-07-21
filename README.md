# mimosaminimal theme for wordpress

![demo image](https://github.com/danilosierrac/mimosaminimal/blob/master/mimosaminimal5.png?raw=true)

### [click here to download theme](https://github.com/danilosierrac/mimosaminimal/raw/master/mimosaminimal.zip)

*A responsive, fast wordpress theme based on the ZH2 theme*

mimosaminimal is a responsive, fast, and minimal theme for wordpress based on the zh2 theme and inspired in our website's simplicity. We made the original zh2 themplate more readable, faster, and up-to-date through the use of system fonts and a bit of CSS

It is just 138 Kb size, and has an archives page, a title with tagline and full control of your content for easier blogging.

You can use it in two ways:

1. To display text in a static page
2. To display all your posts in a list-like homepage (recommended)

## How to install:

1. Download the Zip file from this repo
2. Install on your wordpress environment

## How to setup in your wordpress environment

### First Impressions

When you just install it, you might find that it doesn’t work right out of the box. That’s because it was personally customized by the original author. Luckily he is a true minimalist and the code is relatively simple and small, and I did some bit of a cleanup from the redundancies, specially in the CSS part.

You can go ahead In the WordPress theme editor (Appearance -> Editor), open the following template files and make changes.

The front page won’t look nice at the beginning. This is because the theme is set up to show only one post on the front page, but your settings have more than one post showing. Go to WordPress Settings -> Reading and change Blog pages show at most to “1”.

### Header
Just set up your blog’s title and description are set up correctly in the WordPress Settings -> General.

### Archives page
First create a WordPress page called “Archives” and under the Page Attributes setting in the Page editor, choose “archives” from the list of drop-down templates.

**To see See all Posts on the front page**: At the bottom of the front page, below the single post on the page, is a big “See all posts” link … this goes to the archives page.

### Permalink Structure
Also, the archives are set up for the original design permalink structure, which is “http://mydomain.com/postname/“. You can change your structure to this if you want — in WordPress Settings -> Permalink structure, choose “custom structure” and enter: /%postname%/. Otherwise, you’ll need to change the code in the archives to reflect your permalink structure. I haven’t looked up how to do this, but I’m sure it isn’t that hard.

###Style.css
I tweaked all the styles for fonts, colors, links, etc to make it more readable and up to date with the current design environments. It has the San Francisco, Roboto, Helvetica, and Arial fonts coded in it. As the original author suggest,s feel free to mess with everything to get the look you want. I do it all the time.

###Comments
This template has the ability to have comments into this theme. Just make sure your comments are turned on in the Settings -> Discussion options, and the comments should work. I haven’t tested this extensively, so let me know how it works.
Note: I, as the original author, don’t offer support for this theme, but if there are problems/questions, you can ask here.

*Instructions and text adapted to this template version from the original.* 

#  Feel free to send pull requests to the specific files to make this template a bit more fun. The .zip file includes only the version I uploaded.

🖥

A blog post will look like this:
![demo image](https://github.com/danilosierrac/mimosaminimal/blob/master/screencapture-localhost-8888-template-editing-post-with-photo-1500552713385.png)
