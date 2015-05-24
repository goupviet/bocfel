## December 16, 2014 ##
### Bocfel 0.6.3.2 ###
  * Fix detection of Sherlock version 26-880127.

## June 13, 2014 ##
### Bocfel 0.6.3.1 ###
  * Fix a potential use of uninitialized variable.

## Febrary 2, 2014 ##
### Bocfel 0.6.3 ###
  * Improved handling of abbreviations (x, g, z, and o).
  * The “attribute 48” bug of Sherlock is now properly handled.
  * Blorb sounds are now properly loaded if the story file itself is wrapped in a Blorb file.
  * Support for “debugging” meta commands, the main use of which is to help find cheats without needing to know details of the Z-machine architecture.

## December 1, 2012 ##
### Bocfel 0.6.2 ###
  * Enable /undo in V5 games which do not support undo (e.g. Hitchhiker’s Guide).
  * Add new meta commands /say (allowing text strings which begin with / to be sent to the game) and /disable (which disables meta commands for the rest of the game session).
  * Add new meta commands /ps and /pop which allow in-memory saves to be created, providing arbitrary save points.
  * Meta commands are no longer included in transcripts.

## February 27, 2012 ##
### Bocfel 0.6.1 ###
  * Bocfel is now dual-licensed under both the GPLv2 and GPLv3.
  * Small bugfixes and general cleanup.

## June 26, 2011 ##
### Bocfel 0.6.0 ###
  * The configuration options script\_on and script\_name have been renamed to record\_on and record\_name.
  * Support for some meta commands (/undo, /replay, etc.) has been added.
  * Assorted minor bugfixes and features.

## April 22, 2011 ##
### Bocfel 0.5.5 ###
  * Preliminary @sound\_effect support.
  * Small bugfixes and general cleanup.

## March 25, 2011 ##
### Bocfel 0.5.4 ###
  * Fix a rather obscure bug triggered when @restart is called inside an interrupt.
  * Improved resilience in the face of utterly broken story files.
  * Minor improvements to the syntax for cheats.
  * Improved handling of the configuration file on Windows.

## March 9, 2011 ##
### Bocfel 0.5.3 ###
  * The initial random seed can now be read from a device such as /dev/random.
  * Support for Z-machine versions 1 and 2 is now built unconditionally.
  * Small bugfixes and general cleanup.

## February 22, 2011 ##
### Bocfel 0.5.2 ###
  * Fix a display problem when a newline is printed at the right edge of the upper window.
  * Provide better diagnostics when a save file cannot be loaded.

## February 18, 2011 ##
### Bocfel 0.5.1 ###
  * Bocfel now reports itself as a Standard 1.1-compliant interpreter.
  * The stack is now properly saved in a @save\_undo call.
  * Bocfel generates error messages on a few rather questionable uses of the Z-machine; some of these instances have been modified to return sensible results instead of aborting.  The praxix and strictz tests are now passed.

## February 15, 2011 ##
### Bocfel 0.5.0 ###
  * Initial release.