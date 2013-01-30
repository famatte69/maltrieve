Maltrieve
=========

Maltrieve originated as a fork of [mwcrawler](https://github.com/ricardo-dias/mwcrawler). It retrieves malware directly from the sources as listed at a number of sites, including:

* [Malware Domain List](http://www.malwaredomainlist.com/hostslist/mdl.xml)
* [VX Vault](http://vxvault.siri-urz.net/URL_List.php)
* [Malc0de](http://malc0de.com/rss)
* [Sacour.cn](http://www.sacour.cn)

Pending sources include:

* http://urlquery.net/
* http://www.malware.com.br/cgi/submit?action=list
* http://support.clean-mx.de/clean-mx/xmlviruses.php?
* http://www.nictasoft.com/ace/malware-urls/

These lists will be implemented if/when they return to activity.

* [Malware Black List](http://www.malwareblacklist.com/mbl.xml)
* [NovCon Minotaur](http://minotauranalysis.com/malwarelist-urls.aspx)


Other improvements include:

* Proxy support
* Multithreading for improved performance
* Logging of source URLs
* Multiple user agent support
* Better error handling

Dependencies
------------
* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) version 4

How you can help
----------------

Aside from pull requests, non-developers can open issues on [Github](https://github.com/technoskald/maltrieve). Things we'd really appreciate:

* Bug reports, preferably with error logs
* Suggestions of additional sources for malware lists
* Descriptions of how you use it and ways we can improve it for you

If you'd prefer not to open an issue, you can [contact me on Twitter](https://twitter.com/kylemaxwell) or [email](mailto:krmaxwell@gmail.com).
