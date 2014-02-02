TESDumpStats
============

Dump very basic statistics about ES plugins (record counts, subrecord counts, etc)

This is a command line utility only, with a few options.  TESDumpStats.py must be placed in the Skryim Data directory to run.  Eventually it will may be updated to be able to run from anywhere, and to be compatible with other TES games.  By default, TESDumpStats will dump data on Skyrim.esm, Update.esm, and other official plugins only.  To change this behavior, follow the command line switches.

* -a, --all
 
 After processing Skyrim.esm, Update.esm and other official plugins, the program will proceed to dump stats on all remaining plugins in the Data directory.

* -p 'plugin_name', --plugin 'plugin_name'

  Process only the specified plugin.
  
* -o 'output_directory', --output 'output_directory'

  By default, the dump of the plugin stats will be do Skyrim\Data\TESDumpStats.  Use this to redirect the output.
  
* -s, --split

  By default, the dumps of the plugins will be all in one file.  Use this option to split them into a seperate dump file for each plugin.
