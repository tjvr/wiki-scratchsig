A simple MediaWiki extension for Scratch-style wiki talk signatures.

Uses the 2.0 site API to fetch avatar thumbnail image URLs:

    http://scratch.mit.edu/site-api/users/all/{username}/


Installation
============

Just drop this folder into MediaWiki's "extensions/" folder, and add

    require_once( "$IP/extensions/ScratchSig2/ScratchSig2.php" );

to your "LocalSettings.php".

