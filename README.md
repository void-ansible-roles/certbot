certbot
=======


What is does this role do?
--------------------------

This role installs and manages certbot, an ACME-CA tool which grants certificates using the letsencrypt project.


Meta
----

Files Managed:
  * /etc/cron.d/certbot
  * /etc/letsencrypt/live/[DOMAIN]/fullchain.pem

Defaults Provided:
  * None

Variables Required:
  * None

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * None
