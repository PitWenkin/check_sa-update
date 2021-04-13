# check_sa-update
Nagios/Icinga script to check if spamassassin is up-to-date

It's based on https://exchange.nagios.org/directory/Plugins/Email-and-Groupware/SpamAssasin/check_sa-2Dupdate/details

with the addition of the some code found in the comments

Possible outputs are:

- SA OK - Spamassassin signatures are all up to date
- SA WARNING - Update Available, System not current
- SA CRITICAL - Site pre files do not pass lint check
- SA ERROR - sa-update returned error code `error code`
