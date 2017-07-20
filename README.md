# Alt-Slideshow
Alt-slideshow is an alternatively styled slideshow as a part of my Alt project.
Alt-slideshow contains elegant pictures slideshows with immersive effects.

# help

## Special Notes
The HTML5 Audio with Flash fallback is optional. The Flash does not need to be edited as it will extract the song settings from the HTML5 tags. Only one song is supported.

Eveything is editable and you don't have to use the footer, info or control assets. Check out the menu link "Editing Display Elements" for more information.

If your site doesn't use the "html5" doc-type, that's ok. The gallery will still work.

Autoplay Music is not available for iPhone or iPad. Apple does not allow autoplay for HTML5 Audio and forces the user to click a button in order to activate music. You can still use autoplay for your gallery, but it will be automatically diabled for the iPhone and iPad.

You may notice that the transitions are slightly different for the "stretch" and the "fit" display modes. When cross-fading "fit", because images are often different sizes the transition isn't as seemless as the "stretch" cross-fade. To account for this, "fit" does not implement cross-fade.

If only one category is used, the category title will be automatically hidden.

## API Calls

There are 3 API calls you can make to get information about the gallery.

1.jQuery.bgSlideshow.getIsOn() // returns the current image number in the current gallery (starts with an index of 0)
2.jQuery.bgSlideshow.getCatOn() // returns the current category number (starts with an index of 0)
3.jQuery.bgSlideshow.getHash() // returns the current deep-link url String
