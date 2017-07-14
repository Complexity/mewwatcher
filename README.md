# mewwatcher

Designed to poll *already known* suspicious domains to see if they are still up.

Add domains to sources/detected_sites.txt
They will be sorted into sources/detected_sorted.txt

Then we poll for activity.

TODO:
Add more info about the types of attack (PHP version, AWS JS hosted version etc)

Get a Google Dev key and query the Google Safebrowsing api to see if they have been successfully blacklisted
