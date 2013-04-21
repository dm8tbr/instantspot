instantspot
===========

Spaceapps 2013 participation entry sources and documentation.

I've forked jcfigueiredo/XMPP-Bot
It looks like a useful light weight bot that will suite my needs.
Completed 'stories':
 - report the current ISS position when sent 'now'
 - report the next passes when sent coordinates (dropped in favor of following)
 - accept other forms than coordinates
  - city
  - country
  - use OSM and their APIs for this? (idea from other group at Demola)
   - bingo! http://wiki.openstreetmap.org/wiki/Nominatim#Search
 - return name of location if available (for 'now' queries)
 - set up demo
  - xmpp:instantspot@jabber.bfst.de (also works for google talk)
  - msn:instantspot@ruecker.fi
  - yahoo:instantspotorbit@yahoo.com
  - call +496104667071 from mobile phone - receive next pass over Tampere by text message!


Activities:
 - lots of discussion with local teams in the NewFactory venue
 - discussions on freenode IRC on #spaceapps
 - following and posting on twitter, collaborating with other teams
 - hackpad reading and writing to it

Story backlog:
 - set up demo
  - with icq
  - with twitter (dm? or public?)
  - with text message (bi-directional, sms, through aspsms/swissjabber or voipdiscount)
  - with skype
  - with facebook(is there a working transport?)
  - with phone call, reply with next pass over country where call originated from
  - with phone call, reply with next pass over location registered for phone number
 - send notification of upcomming pass for previously set coordinates
 - return magnitude of pass and other info
 - find way to get altitude information for lat/lon tuple
 - find way to calculate timezone/dst for lat/lon and return local time
 - accept other forms of location
  - identify country by phone prefix (SIP gateway)
  - any XEP that would allow to retrieve remote location?
 - reply directly to phone call and use TTS (festival)
 - move from remote json queries to locally stored and updated TLE
 - add support for arbitrary objects found in TLE file
 - add support for objects outside of earth orbit
 - add search in TLE objects
