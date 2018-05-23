# TextToImage
A Drupal 8 Module that takes a short post &amp; creates an image from the text of the post. 

## Problem/Motivation
I currently write poems in Google Keep, screenshot them, and then post to Instagram.  I would like to simplify this workflow and centralize content creation on my own site, rather than on third-party systems like instagram. 

## Proposed resolution
Ideally the workflow looks like this: 
1. Post poem on Drupal 8 site
2. Poem is converted to nicely formatted image. 
3. Poem is posted to Instagram with a link referencing the original source on my site (possibly with the poem itself as alt text in the caption, along with specified hashtags). 

Unfortunately Instagram doesn't allow users like me to programmatically post from outside the web app (to my knowledge). 

A revised workflow could look like this: 
1. Post poem on Drupal 8 site. 
2. Poem is converted to nicely formatted image. 
3. Poem image & caption text is synced somewhere that makes it easier to post on Instagram. 

## Remaining tasks
1. Build out image converter.
2. Add fields to control layout.
3. Add fields to specify which posts are to be converted to images.
4. Build connector to Instagram. 
