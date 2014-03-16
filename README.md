Plupload2-image-w-h-filter
==========================

Example of width and height filter for [Plupload 2 ](http://www.plupload.com/)

=====

Plupload started in a time when uploading a file in a responsive and customizable manner was a real pain.
Internally, browsers only had the `input[type="file"]` element. It was ugly and clunky at the same time.
One couldn't even change it's visuals, without hiding it and coding another one on top of it from scratch.
And then there was no progress indication for the upload process... Sounds pretty crazy today.

It was very logical for developers to look for alternatives and writing their own implementations, using
Flash and Java, in order to somehow extend limited browser capabilities. And so did we, in our search for
a reliable and flexible file uploader for
our [TinyMCE](http://www.tinymce.com/index.php)'s
[MCImageManager](http://www.tinymce.com/enterprise/mcimagemanager.php).

Quickly enough though, Plupload grew big.  It easily split into a standalone project.
With major *version 2.0* it underwent another huge reconstruction, basically
[from the ground up](http://blog.moxiecode.com/2012/11/28/first-public-beta-plupload-2/),
as all the low-level runtime logic has been extracted into separate [File API](http://www.w3.org/TR/FileAPI/)
and [XHR L2](http://www.w3.org/TR/XMLHttpRequest/) pollyfills (currently known under combined name of [mOxie](https://github.com/moxiecode/moxie)),
giving Plupload a chance to evolve further.