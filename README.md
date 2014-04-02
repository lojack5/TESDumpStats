TESDumpStats
============

Dump very basic statistics about ES plugins (record counts, subrecord counts, etc)

This is a command line utility only, with a few options.  TESDumpStats.py must be placed in the Game's Data directory to run.  Eventually it will may be updated to be able to run from anywhere.  By default, TESDumpStats will dump data on the Game's official plugins only.  To change this behavior, follow the command line switches.

* -a, --all
 
 After processing the Game's official plugins, the program will proceed to dump stats on all remaining plugins in the Data directory.

* -p 'plugin_name', --plugin 'plugin_name'

  Process only the specified plugin.
  
* -o 'output_directory', --output 'output_directory'

  By default, the dump of the plugin stats will be to Data\TESDumpStats.  Use this to redirect the output.
  
* -s, --split

  By default, the dumps of the plugins will be all in one file.  Use this option to split them into a seperate dump file for each plugin.

* -O, --Oblivion, --oblivion

  By default, the program assumes plugins are written in the format of Fallout 3, Fallout: New Vegas, or Skyrim.  Use this switch to specify the Oblivion format (for processing Oblivion's plugins).
