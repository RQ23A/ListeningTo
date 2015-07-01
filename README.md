# ListeningTo

ListeningTo combines pidgin-state.py script, created by miljank (user from GitHub), with a bash script that collects artist and song data from Spotify using dbus.

So when running the python script in it's deamon mode, it will call the bash script and generate a text file where the scripts gets the data and push it to Pidgin status bar.

Example:

python pidgin-status.py -f data.txt -d -t 0.1

-f asks for the file where the bash scripts saves the data from spotify
-d runs as deamon
-t time in minutes to sleep between bash execution and status push
