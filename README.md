# WP-Upload-WEPB-Files-plugin
a small lug n for wp tp allow users to upload wepb files. does what it says
---

=== WP WebP Uploads ===
Contributors: TABARC-Code made origionally for https://www.gameshaven.co.uk now just sharing.
Tags: webp, uploads, media, images, gameshaven
Requires at least: 5.8
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Allows the WordPress site to upload and use WebP images in the media library.

== Description ==

 WebP Uploads enables safe `.webp` uploads for Wordpress by registering the WebP MIME type and correcting file validation on hosting environments that do not recognise WebP files automatically.

The plugin checks the uploaded file header before treating a file as WebP, so a renamed non-image file is not blindly accepted.

== Installation ==

1. Upload the `webp-uploads` folder to `/wp-content/plugins/`.
2. Activate ** WebP Uploads** in **Plugins**.
3. Upload `.webp` images through **Media > Add New** or the block editor.

== Frequently Asked Questions ==

= Does this support `.wepb` files? =

The WebP image extension is `.webp`. If you meant `.wepb`, rename the file to `.webp` before uploading.

= Will WordPress generate thumbnails for WebP files? =

Only if the server's GD or Imagick image library supports WebP. The plugin shows an admin warning on media screens if uploads are enabled but image editing support is missing.

== Changelog ==

= 1.0.0 =
* Initial Games Haven branded WebP upload support.
