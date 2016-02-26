# What is ReGalAndroid ? #

ReGalAndroid (RemoteGallery client for Android) is an open source (GPL v3) [G2](http://codex.gallery2.org/Gallery3:About),[G3](http://codex.gallery2.org/Gallery3:About) and [Piwigo](http://piwigo.org/) client for the Android platform; it aims at providing the best integration possible of a remote gallery on Android; better than browsing the web gallery with the integrated webkit browser.

ReGalAndroid is the followup of [G2Android](http://code.google.com/p/g2android/); G2Android only provided support for G2 and its development is now over; G2Android is dead, long live ReGalAndroid !


ReGalAndroid can run on Android from version 1.5 to the latest (it has been tested on various phones and tablets from 1.5 to 2.3)

Your gallery must have remote api access enabled ;
  * with G2 [make sure remote module is installed and enabled](http://codex.gallery2.org/Gallery2:FAQ#Gallery_Remote_can.27t_find_my_G2.2C_what.27s_wrong.3F)
  * with G3 [enable the rest access](http://codex.gallery2.org/Gallery3:API:REST#Enabling_REST_access)
  * with Piwigo, you have to enable the plugin pwg.images.addSimple to be able to upload photos

# What's new ? #
Latest version is 1.1.2, released on the 23rd of October 2011, bug fixes; have a look at the ReleaseNotes


# Where can I download ReGalAndroid ? #
  1. You can download it directly from this project site download section : http://code.google.com/p/regalandroid/downloads/list

  1. You can download it from the [Android Market](https://market.android.com/details?id=net.dahanne.android.regalandroid)
    * from the android market, search **ReGalAndroid** ,
    * or type in your android device browser : market://search?q=pname:net.dahanne.android.regalandroid
    * or scan this QR Code with a barcode scanner for Android :
![https://github.com/anthonydahanne/ReGalAndroid/raw/master/art/qrcode-small.png](https://github.com/anthonydahanne/ReGalAndroid/raw/master/art/qrcode-small.png)


# What are the supported features ? #
As of version 1.1.x
  * Sharing and sending photo (via twidroid and mail for example)
  * Jump to photo feature
  * Full screen navigation
  * Cache feature (speeds up the navigation a lot)
  * I18N (french, spanish, german, chinese zh\_CN and zh\_TW, please contribute translation in your language : [as easy as translating those values!](https://github.com/anthonydahanne/ReGalAndroid/blob/master/regalandroid/res/values/strings.xml))
  * browsing the albums
  * browsing and displaying the pictures
  * uploading a photo to the gallery
  * creating a new sub album
  * send one or many photos from Android gallery app
  * take a picture (using the camera) and send it to the remote gallery

please have a look at ReleaseNotes to know the details of each release and what are the currently supported features!


## How can I show my support to this application ? ##

You can [fill a bug or solve an issue](http://code.google.com/p/regalandroid/issues/list) , [have a look at the code to make it better](https://github.com/anthonydahanne/ReGalAndroid), and , [translate it into your language](https://github.com/anthonydahanne/ReGalAndroid/blob/master/regalandroid/res/values/strings.xml) it is very easy !

If you have a spare Android device, you can send it to me so that I can test on more platforms ! Contact me at anthony.dahanne@gmail.com

Finally, if you like this app, you can flattr me !
[![](http://api.flattr.com/button/flattr-badge-large.png)](http://flattr.com/thing/93967/ReGalAndroid)

## Reusing the gallery2, gallery3 and piwigo libraries in your Android or plain Java application ##

Looking at the [github project homepage, you will find](https://github.com/anthonydahanne/ReGalAndroid) you will notice that there is a project for each gallery type implementation : g2-java-client, g3-java-client and piwigo-ws-converter
Using Maven, you can reference them in your project pom as dependencies, adding this repo coordinates :
```
<repositories>
    <repository>
      <id>nexus.dahanne.net-snapshots</id>
      <url>http://nexus.dahanne.net/nexus/content/repositories/snapshots/</url>
    </repository>
    <repository>
      <id>nexus.dahanne.net-releases</id>
      <url>http://nexus.dahanne.net/nexus/content/repositories/releases/</url>
    </repository>
  </repositories>
```
Feel free to reuse those implementations in your apps, as long as you respect the GPL v3 license.

## What are G2, G3 and Piwigo ? ##
G2, G3 and Piwigo are among the most popular open source projects for hosting your photos on your website.
Unlike Picasa Web or FlickR,they are softwares you have to install on your Php/MySQL server to host your photos : the main advantage is that you have full control over your galleries.

They are also open source projects, very popular and have many clients and plugins !

You can learn more about G2 and G3 visiting their project website : http://gallery.menalto.com , and you can see some live galleries at : http://gallery.menalto.com/gallery/demosites/

You can learn more about Piwigo visiting its project website : http://piwigo.org/ , and you can see a demo live gallery at : http://piwigo.org/demo/

# Screenshots #
These screenshots were taken from ReGalAndroid Version 1.0.0

![https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/title.png](https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/title.png)
![https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/settings.png](https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/settings.png)
![https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/gallery_type.png](https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/gallery_type.png)
![https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/browsingalbum.png](https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/browsingalbum.png)
![https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/browsingpicture.png](https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/browsingpicture.png)
![https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/picture-options.png](https://github.com/anthonydahanne/ReGalAndroid/raw/master/screenshots/picture-options.png)
![http://blog.dahanne.net/wp-content/uploads/g2android-upload-photo.png](http://blog.dahanne.net/wp-content/uploads/g2android-upload-photo.png)
![http://blog.dahanne.net/wp-content/uploads/g2android-upload-photos.png](http://blog.dahanne.net/wp-content/uploads/g2android-upload-photos.png)