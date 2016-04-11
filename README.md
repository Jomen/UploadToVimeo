# UploadToVimeo

In this app I try to use Polymer to upload video to a Vimeo.com account with only a accessToken.

There are some problems that needs to be dealt with.

Console log shows: 

[vimeo-upload::_createEventHandler]: listener method `{{handleFileChanged}}` not defined

[vimeo-upload::_createEventHandler]: listener method `{{handleUploadClicked}}` not defined


although the script with handleFileChanged and handleUploadClicked is in the same vimeo-upload.html


Vimeo-upload.html is a modification of the original page at https://gist.github.com/websemantics/94f0fcb43458ccff5535 


The app needs to be run with a server service in app root.

grunt

grunt serve
