# sailitDump

Dump sailit to-dos (done) into a nested directory structure with markdown.

## What is Sailit

Sailit is a nested to-do list for Sailfish OS.

## Requirements

* sqlite3

## Using it

1. On your sailfish device, look in `.local/share/harbour-sailit/harbour-sailit/QML/OfflineStorage/Databases` for a file with a name ending in `.sqlite`.
1. Get that file to what ever device you want to run this script in.
1. Run `sailitDump filename.sqlite` . This may take a minute or two depending on how many entries you have. It turns out that mine was hunmoungus.

You should now have a directory named `root`. In there are all the lists and entries that you have in Sailit.

You can see how many entries have been imported by running `countEntries` in the directory named `root` .
