munin-regenwolken
=================

Creates Munin graphs from the status data every Regenwolken instance provides.

Install
-------

Clone this repository or download the rw_ file and create a
symlink as *root* in /etc/munin/plugins by using e.g.:

	cd /etc/munin/plugins; ln -s /path/to/rw_ rw_<option>

where <option> is one of users|files|size|hits.

**Don't forget to restart your munin-node deamon.**
