# Analysis 
Both HUGO and Jekyll are Static Site Generators.

## Jekyll
* Installation
	* Jekyll installs as a RubyGem. 
	* Needs pre-installed and configured Ruby environment.

* Extensibility
	* Plugins API provides ability to write short code snippets to extend functionality.
	* Plenty of plugins available in the community.

* Migration from Wordpress
	* Third party tools available to migrate from wordpress
	* Migration is not as straight forward as it is to HUGO.

* Performance
	* Build speed is slow for content heavy websites. 
	* No I18N support, No support for XML Sitemaps, RSS / Atom Feeds.
	* Plugin available for AMP to generate AMP markup.

## HUGO
* Installation
All in one Binary for installation.

* Extensibility
  * Plenty of built-in features gives advantage to HUGO. But lacks on plugin support. Adding custom functionality is questionable.
  * Supports external data which can be pulled from REST APIs. 

* Migration from Wordpress
  * Third party tools available to migrate from wordpress.
  	* wordpress-to-hugo-exporter 
  	* exitwp-for-hugo
  	* Also supports conversion from Jekyll using jekyll import command in HUGO 

* Performance
	* Fast builds
	* I18N support, XML Sitemaps, RSS / Atom Feeds generation.
	* Custom output format will enable us to generate static website, an alternate Google AMP website, and consumable JSON files for a mobile application all at once.

## Gatsby
* In addition to the above two, Gatsby is the latest Static Site Generator build on node.js and uses Reactjs for the client side.
* Gatsby generates Progressive Web Apps.
* It is slow compared to the above 2 options.

## Verdict
Based on my research within the limited time, I would recommend HUGO. Since our primary requirement is to deliver content in the most remote regions where there is limited network connectivity, HUGO serves the purpose best.

However, before making the actual decision, I would like to try both Jekyll and HUGO, spend atleast 4-6 hours on each to get a thorough idea about both.