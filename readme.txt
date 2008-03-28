=== MD5 Password Hashes ===
Contributors: ryan
Tags: login, password, md5
Requires at least: 2.5
Tested up to: 2.5
Stable tag: 1.0.1

Changes the password hashing in WordPress to use MD5

== Description ==

This plugin reverts storage of user passwords back to using MD5 hashing
instead of the newer phpass hashing introduced in 2.5.

It is useful for people who need to maintain MD5 as the hashing type due to
sharing of the WordPress user tables with other applications which require it.

If some of your passwords are already converted to phpass, do not fear. The
next time those users log in to WordPress their passwords will be converted back
to MD5.

== Installation ==

1. Upload the plugin into /wp-content/plugins/ directory

2. Activate the plugin

== License ==

MD5 Password Hashes 1.r01
Copyright (C) 2008 Ryan Boren

MD5 Password Hashes comes with ABSOLUTELY NO WARRANTY
This is free software, and you are welcome to redistribute
it under certain conditions.

See accompanying license.txt file for details.

== Version History ==

* 1.0 : 
  <br/>Initial Release
