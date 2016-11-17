# nagios-pydio-licenses
Nagios plugin for monitoring Pydio licenses

Usefull only if you have a commercial license for Pydio

This plugin for Nagios implements a "check" command. 
It returns an alert if the license is about to expire, or if the number of users is too close from the maximum allowed.

It uses the REST API of Pydio.
