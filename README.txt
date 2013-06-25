Simple MediaWiki extension for wiki talk signatures with Scratch avatars.

Uses the Scratch 2.0 site API to fetch avatar thumbnail image URLs:

    http://scratch.mit.edu/site-api/users/all/{username}/


Installation
============

Just drop this folder into MediaWiki's "extensions/" folder, and add

    require_once( "$IP/extensions/mw-ScratchSig2/ScratchSig2.php" );

to your "LocalSettings.php".

