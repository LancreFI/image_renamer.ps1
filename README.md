# image_renamer.ps1
PowerShell script to rename multiple files within a dir to have their timestamp as the name

My first ps-script, so might not be very pretty nor have the most efficient way of doing things :D

Run (with ISE or your choise of tool):
.\image_renamer.ps1

Asks for the directory in which the files are located. Make sure the dir contains only files, no subdirs or anything, as the behaviour's not tested on subdirs. Don't put the script inside the same dir either.

You can choose to use the last modification date or the Date taken -value from metadata (image files) as the new filename (ddMMyy_HHmmss.extension).

Created this as an introduction into PowerShell for myself when doing cloud backups of my thousands of photos. At least the service I'm using alters the timestamps, so the only way of knowing the actual date taken is by using it in the filename.
