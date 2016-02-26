# Version 1.1.2 , released on Sundays the 23rd of October 2011 : better g3 support #
## Issues solved ##
  * [Issue #6](https://code.google.com/p/regalandroid/issues/detail?id=#6): 	G3 : HTTP 414 error when loading albums with many pictures
  * [Issue #10](https://code.google.com/p/regalandroid/issues/detail?id=#10): 	G3 : Request: Album Thumbnails
  * [Issue #54](https://code.google.com/p/regalandroid/issues/detail?id=#54): 	G3 : the sub-albums are not displayed (even if logged in)
  * [Issue #67](https://code.google.com/p/regalandroid/issues/detail?id=#67): 	FC : java.lang.NullPointerException ShowGallery.onResume(ShowGallery.java:127)
  * [Issue #68](https://code.google.com/p/regalandroid/issues/detail?id=#68): 	FC : java.lang.IllegalArgumentException URI.create() Illegal character in path
  * [Issue 69](https://code.google.com/p/regalandroid/issues/detail?id=69): 	FC : java.lang.NullPointerException net.dahanne.android.regalandroid.utils.AndroidUriUtils.extractFilenameFromUri(AndroidUriUtils.java:65)
  * [Issue 40](https://code.google.com/p/regalandroid/issues/detail?id=40): 	G3 : when too many sub albums, none of them are displayed
  * [Issue 63](https://code.google.com/p/regalandroid/issues/detail?id=63): 	G3 : Main album is empty ('This album does not contain any pictures!')

and new Spanish translation thanks to https://github.com/mrnmart, corrections to German translation thanks to Karl Shofer, corrections to Chinese translations thanks to https://github.com/dtsang29 and many thanks to mccar for his patch on [issue #10](https://code.google.com/p/regalandroid/issues/detail?id=#10)

# Version 1.1.1 , released on Thursday the 20th of October 2011 : honeycomb support #
## Issues solved ##
  * [issue #82](https://code.google.com/p/regalandroid/issues/detail?id=#82) : g3 : if comments are disable, did not work
  * [issue #83](https://code.google.com/p/regalandroid/issues/detail?id=#83) : honeycomb support downloading the thumbs in a non UI thread


# Version 1.1.0 , released on Saturday the 23rd of April 2011 : Upload to G3 & Piwigo beta support #
## Issues solved ##
  * [issue #45](https://code.google.com/p/regalandroid/issues/detail?id=#45) : G2 : can not upload picture : Text may not be null
  * [issue #22](https://code.google.com/p/regalandroid/issues/detail?id=#22) : on large display, full size picture should scale
  * [issue #39](https://code.google.com/p/regalandroid/issues/detail?id=#39) : All : remove "No summary available" label when no summary is available


## New features ##
  * German translation by Ralph Kapsammer (thank you !)
  * G3 beta support for uploading & album creation
  * Piwigo beta support for uploading & album creations (**you have to install the Piwigo plugin pwg.images.addSimple** on your Piwigo Gallery)
  * [issue #51](https://code.google.com/p/regalandroid/issues/detail?id=#51) : G3 - add support for url rewriting (nice urls)
  * [issue #53](https://code.google.com/p/regalandroid/issues/detail?id=#53) : Allow installation to SD card





# Version 1.0.1 , released on Sunday the 16th of January 2011 Bug fixes #
## Issues solved ##
  * [issue #23](https://code.google.com/p/regalandroid/issues/detail?id=#23) : User-Agent label needs updating
  * [issue #32](https://code.google.com/p/regalandroid/issues/detail?id=#32) : G3GalleryException: Value null at owner\_id of type org.json. JSONbject$1 cannot be converted to int
  * [issue #33](https://code.google.com/p/regalandroid/issues/detail?id=#33) : G2Connection.getAlbumAndSubAlbumsAndPictures(G2Connection.java:87) NPE [reported by users via Android Market](crash.md)
  * [issue #38](https://code.google.com/p/regalandroid/issues/detail?id=#38) : G3GalleryException: Value [.md](.md) at relationships of type org.json.JSONArray cannot be converted to JSONObject

## New features ##
  * No new features :-(



# Version 1.0.0 , released on Tuesday the 21st of December #
## Issues solved ##
  * [issue #4](https://code.google.com/p/regalandroid/issues/detail?id=#4) : Screen resolution
  * [issue #7](https://code.google.com/p/regalandroid/issues/detail?id=#7) : share feature fault
  * [issue #11](https://code.google.com/p/regalandroid/issues/detail?id=#11) : impossible to see pictures in root album
  * [issue #16](https://code.google.com/p/regalandroid/issues/detail?id=#16) : filenames with accents
  * [issue #20](https://code.google.com/p/regalandroid/issues/detail?id=#20) : App Loses Connection and Starts Over when Screen is Flipped
  * [issue #8](https://code.google.com/p/regalandroid/issues/detail?id=#8)	Feature request: display number of pictures in album

## New features ##
  * Sharing and sending photo (via twidroid and mail for example)
  * Jump to photo feature
  * Full screen navigation
  * Cache feature (speeds up the navigation a lot)
  * I18N (french, chinese zh\_CN and zh\_TW, please contribute translation regalandroid in your language is as easy as translating those values!)
  * browsing the albums
  * browsing and displaying the pictures
  * displaying the number of pictures in each album
  * uploading a photo to the gallery--only for G2 galleries
  * creating a new sub album--only for G2 galleries
  * send one or many photos from Android gallery app--only for G2 galleries
  * take a picture (using the camera) and send it to the remote gallery--only for G2 galleries
