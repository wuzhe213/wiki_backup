# wiki_backup

wiki backup files created environment:

os: linux minet 17 mate (based on ubuntu 14.04)

mediawiki installed by synaptic Package Manager, with extention: geshi

How to restore:
get basic mediawiki installed
create mysql database. database informaton can be found in LocalSettings.php
copy LocalSettings.php to /var/lib/mediawiki
change the value of wgDBpassword in LocalSettings.php
change the value of wgServer in LocalSettings.php

(change wikidb wikiuser to your names)
mysql -u root -p
create database wikidb;
CREATE USER 'wikiuser'@'localhost' IDENTIFIED BY 'PASSWD';
GRANT ALL PRIVILEGES ON wikidb.* TO 'wikiuser'@'localhost' WITH GRANT OPTION;
use wikidb
source wikidb-20120927.sql
