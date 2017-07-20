# Alt-Slideshow
Alt-slideshow is an alternatively styled slideshow as a part of my Alt project.
Alt-slideshow contains elegant pictures slideshows with immersive effects.

# help

<h3>Special Notes</h3>
                
                <ul>
                    <li>The HTML5 Audio with Flash fallback is optional.  The Flash does not need to be edited as it will extract the song settings from the HTML5 tags.  Only one song is supported.  Please contact me from the form on the link below if you need a more advanced music player as I am available for freelance projects.</li>
                    <li>Eveything is editable and you don't have to use the footer, info or control assets.  Check out the menu link "Editing Display Elements" for more information.</li>
                    <li>If your site doesn't use the "html5" doc-type, that's ok.  The gallery will still work.</li>
                    <li>Autoplay Music is not available for iPhone or iPad.  Apple does not allow autoplay for HTML5 Audio and forces the user to click a button in order to activate music.  You can still use autoplay for your gallery, but it will be automatically diabled for the iPhone and iPad.</li>
                    <li>You may notice that the transitions are slightly different for the "stretch" and the "fit" display modes.  When cross-fading "fit", because images are often different sizes the transition isn't as seemless as the "stretch" cross-fade.  To account for this, "fit" does not implement cross-fade.</li>
                    <li>If only one category is used, the category title will be automatically hidden.</li>
                </ul>
                
                <h3>API Calls</h3>
                
                	<p>There are 3 API calls you can make to get information about the gallery.
                
                	<ul>
                    
                    	<li><b>jQuery.bgSlideshow.getIsOn()</b> // returns the current image number in the current gallery (starts with an index of 0)</li>
						<li><b>jQuery.bgSlideshow.getCatOn()</b> // returns the current category number (starts with an index of 0)</li>
						<li><b>jQuery.bgSlideshow.getHash()</b> // returns the current deep-link url String</li>
                        
                    </ul>
                

