# IMPReSS Tools

`impress2json` will download the entire IMPReSS database and output to a timestamped json document, and symlink to it with a generic name.

If such a file already exists and is up to date, it will exit without downloading.

If such a file already exists and is out of date, the current database will be downloaded, and the symlink will be updated.

It has a "daemon" mode to check for updates, thereby making it more friendly to be used in a system service.  An example systemd service is provided.

Braden has it running on his local machine, and you access the output at http://mbp.dabrado.net/data/impress.json
