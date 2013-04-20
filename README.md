instantspot
===========

Spaceapps 2013 participation entry sources and documentation.

I've forked jcfigueiredo/XMPP-Bot
It looks like a useful light weight bot that will suite my needs.
Completed 'stories':
 - report the current ISS position when sent 'now'

Story backlog:
 - report the next passes when sent coordinates
 - send notification of upcomming pass for previously set coordinates
 - accept other forms than coordinates
  - city
  - country
  - any XEP that would allow to retrieve remote location?
  - use OSM and their APIs for this? (idea from other group at Demola)
 - set up demo
  - with plain XMPP (/should/ work with Gtalk ootb)
  - with icq
  - with msn messenger
  - with yahoo messenger
  - with twitter (dm? or public?)
  - with text message (sms)
  - with skype
  - with facebook(is there a working transport?)
 - move from remote json queries to locally stored and updated TLE
 - add support for arbitrary objects found in TLE file
 - add search in TLE objects
