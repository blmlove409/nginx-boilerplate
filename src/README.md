To install boilerplate copy these files over to /etc/nginx, backing up it's original content.

To further customize your boilerplate edit theses files:
 * nginx-bp/bootstrap/SITE_URL.conf
 * sites-available/SITE_URL.conf

You should not change other files for the possibility of:
 * drop-in installation and independent operation of other generated boilerplate sites 
 * upgrading base boilerplate

Instead try creating new config files and including them from the two mentioned virtualhost definition configs