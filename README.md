# ttFlickr - Under development

This is an attempt to fork the [Wordpress Flickr Embed](https://github.com/hiddentao/wp-flickr-embed) plugin 
(itself a fork of [Wordpress Media Flickr](http://wordpress.org/extend/plugins/wordpress-media-flickr/))
to try and resolve the main issues I'm experiencing with it.

If I'm successful, I'll try releasing it in a way that's useful for others. For now, it is a work in progress.

The main issues I'm trying to address are

1. Images are inserted using static sizes. This is problematic and results in stretched images if the chosen size does not work well with the current template. Use relative sizes instead.
1. Inserting multiple images side by side is either ugly or requires manual setting of size. This is not optimal. My goal is to be able to specify how many images should be displayed per line, and have the size be dynamically calculated.
1. I need the ability to display images that are in my private Flickr feed. This feature is missing in some of the other Wordpress plugins to insert Flickr images.
1. I don't want to display whole galleries. Instead, I want to be able to pick and choose which images I'm inserting.

I don't have time to do this right now. This is a mistake. Hopefully I will realize this and stop working on this project until I finish more important tasks.