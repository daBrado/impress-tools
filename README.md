# IMPReSS Tools

`impress2json` will download the entire IMPReSS database and dump it as a json document with a timestamp of the IMPReSS database's last modified time.

If there already exists a json document with the same timestamp, then the download will not continue, thus making the script suitable for cron jobs.

Braden has it running on his local machine, and you access it via http://mbp.dabrado.net/data/impress.json

(On that machine it takes about 90 minutes to run, so if you only need the data, you might want to grab it from the above link.)
