# Fall Guys Stats - 8.2 Breakfix

This is a fork of the excellent Fall Guys Stats program froim ShootMe: https://github.com/ShootMe/FallGuysStats

In version 8.2.0 of Fall Guys, the logs stopped having timestamps. This update reconstructs the log file by inserting timing data on the fly (requires the stat tracker to be running before starting the show). Round timings won't be exact but appear to be pretty close (within ~0.1 second). All tracking from 8.0.0 should be functional again, aside from the Ping on the overlay. It will create a backup copy of the database file when running this version for the first time.

## Usage

  - Make a backup of your existing Fall Guys Stats folder!
  - Download https://github.com/ThreesFG/FallGuysStats/raw/master/FallGuysStats-8.2-Breakfix-20221030.zip
  - Replace the file "FallGuysStats.exe" in your Fall Guys Stats folder with the one in this .zip file
  - Make sure that the program is running before starting a show in game! - As we're recreating timestamps on the fly, this is required.
  
## Feedback

Please provide feedback https://github.com/ThreesFG/FallGuysStats or on twitter https://twitter.com/ThreesFG . If testing goes well, this will get submitted as a pull request to the main Fall Guys Stats program.
