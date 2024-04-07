# hivebritlist
Generate post of active Hive users based on a list

All designed to run in Jupyter Notebook. Put people in the users.txt file. Lines starting with 'R,' break it down into regions. Can include aliases in brackets. Scripts require an account on HiveSQL.
* FindUsers looks for users with matching location data. Skips those already in users.txt or ignore.txt
* activeuser generates the post by checking for recent activity. Includes graphs.

steemengineteam_group.txt was a list of compromised accounts. This is old, so may not be up to date.
