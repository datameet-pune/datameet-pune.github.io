## Open Projects for DataMeet Pune chapter

Datameet is a volunteer group of civil society & programmers interested in data related issues relevant to the social sector. We work to improve the quality of public information/data on multiple issues such as public transport, education, city budgets, rural development etc. See <http://datameet.org> for more.

On this page, we are attempting to bring together various open data projects that volunteers of DataMeet Pune chapter are working on, or want to work on. Along with the output, we want to document and openly share the work being done as it's happening, in a way that anyone interested can join in and take things forward.

There are broadly three types of work we can do:

 1 Collect | 2 Curate | 3 Apply 
--|--|--
Bring socially relevant data out by collecting, listing, sharing about it | Digitize, curate, clean, convert the data to a better, more usable form | Visualize or otherwise apply the data; combine with other dataset(s) 
example:||
<sub>[official PDF of Pune elected corporators 2017-22](https://pmc.gov.in/sites/default/files/winning_candidates.pdf)</sub> | <sub>[CSV table of the same](https://gist.github.com/datameet-pune/3ca3af1d528623c1bb7d99f8466868f0)</sub> | <sub>[Map of Pune showing which area has elected which corporators](https://nikhilvj.carto.com/viz/718f58d8-8e07-11e6-8015-0e3ff518bd15/embed_map)</sub>

## Projects

### [<img align="right" src="images/bus%20stops%20swargate.jpg" alt="" width="300" height="152" />](images/bus%20stops%20swargate.jpg)PMPML / bus / public transport related:

  * **[Project working log : Pmpml bus stops](https://github.com/datameet-pune/datameet-pune.github.io/wiki/Project%3A-Bus-stops-database)**
  * [project note : pmpml routes](https://docs.google.com/document/d/1ppcf8OiaCWQORqlL8d2gsbo3_6qAordjcow70djeFBk/edit?usp=sharing)
  * [project note : GTFS conversion program](https://docs.google.com/document/d/1XE3blI2zjY6el9voHYF6XtvKJV6m5xXxBjgNq3bYabc/edit?usp=sharing)

### [<img align="right" src="images/punedistchoro.jpg" alt="" width="300" height="261" />](images/punedistchoro.jpg)Maharashtra Villages mapping

  * [Write-up on the project](https://craigdsouza.github.io/village_mapping/)
  * [Tracking sheet](http://tinyurl.com/dmpune17916)
  * Web interface : 
      * [Log of processing shapefile for web interface](https://docs.google.com/document/d/1JzdHpGpuNBqad717gLa2M2hQ1rMMLLv6FWdxw6-b9Cs/edit?usp=sharing)
      * [Choropleth visualization of census data for MH villages](https://bnamita.github.io/Village_Mapping_v2/)
      * [project on github](https://github.com/bnamita/Village_Mapping_v2/tree/master)
      * [upload-your-own-csv version](https://github.com/bnamita/Village_Mapping_v2/tree/Upload-own-csv)

Related : [IndiaWikiFiles](https://github.com/IndiaWikiFiles/Maharashtra) : Wiki files for villages and towns in Maharashtra based on Census 2011 (the project has work going on for other states too)

### Pune wards / elections:

  * Available data: 
      * [New wards boundaries (2017 onwards) digitized](https://gist.github.com/answerquest/db11b5c7be7e00765ae33152124aba1e)
      * [List of candidates contesting for 2017 civic (PMC) elections](https://gist.github.com/answerquest/0cfd125093f891c853befa12226eff79) (cleaned,  searchable)
      * [List of corporators elected in 2017 civic (PMC) elections (serving 2017-22)](https://gist.github.com/datameet-pune/3ca3af1d528623c1bb7d99f8466868f0) (cleaned,  searchable)
      * [Composite map showing new and old boundaries and old corporators&#8217; details](https://nikhilvj.carto.com/viz/718f58d8-8e07-11e6-8015-0e3ff518bd15/embed_map)
  * Data wanted: 
      * Centroid or main chowk etc lat-long location of each ward, to have point-locations of wards
      * 2017-22 elected corporators listng (Marathi+English), details, photos
      * Admin ward allocation of the new 41 wards
      * Polling booth locations for 2017 municipal election

### Pune Budget
* Budget 2017-18 released in excel format: <http://www.punecorporation.org/en/budget-2017-2018>
* See [work done](http://ourpuneourbudget.in/) on 2016-17 budget (data curation, visualization)

### Pune Development Plan

  * [Project note : web-mapping March2017 Development Plan maps for Pune](https://docs.google.com/document/d/1fsrDS6six2zkgZJ_L-10__1yyOUZs4Sj23SbXwBCdYI/edit?usp=sharing)
  * See [overlap.html](http://nikhilvj.cu.cc/files/overlap.html) for seeing past DPs overlapped.

Latest draft DP released in March 2017. Inviting volunteers for &#8220;warping&#8221; the released static maps to web map to enable overlaying, comparing with satellite maps, etc. Click the project note link above for more.

### MSRTC data

  * [List of MSRTC bus stands](https://gist.github.com/answerquest/5d8c85a369d9c3c6d5513743995f7e78) : Bus Stop Code, Bus Stop Name, Taluka name, District Name.
  * To do: assign lat-long co-ordinates to this list. [Google spreadsheet initiated here](https://docs.google.com/spreadsheets/d/1j3ix7Xj-HwnU9t6UJ7jXiCS2gWDnlwLkSpniEJLdYS4/edit?usp=sharing) for crowdsourcing locations.
  * Wanted: MSRTC routes and time tables.

### Satyamey Jayate Water Cup 2017

  * See <http://paanifoundation.in/> and [their Get Involved page](http://www.paanifoundation.in/en/get-involved/) for details.
  * [List of participating villages](http://bit.ly/villagenames) published by Paani Foundation
  * Curated [list of participating villages](https://drive.google.com/open?id=1SyIZ1xqaJk5TTF_LUWsYIdngia1gGho9PUrbs2KWwrw) : table with columns: region, district, taluka, village (marathi and english)

To do:

  * Cross-reference with 2011 census data to get village codes of the participating villages
  * Find shapes and/or lat-long locations from MH Villages shapefile

## Others:

To be detailed out. Here are some brief overview points: List of things we can work on:

  * Mapping: 
      * groundwater data
      * urban farms
      * ranwater harvesting
      * solar water heater adoption
      * composting
      * waste segregation
      * industries / factories
      * govt offices
      * centroids of new wards (point locations)
      * rent, prices

* Learning:
  * Python
  * R
  * javascript
  * mapping &#8211; general, web-based
  * QGIS
  * machine learning, modelling, etc

> Tip : learning happens quicker when there is real world data to work on.
  
> Incentive : learner can publish an output of their learning, like a cleaned up dataset or a viz. This can be a valuable addition to their resume.


## Pune Chapter
Interested in working on any of this? Got a great project of your own and want to find collaborators / support? Want to work on one of these projects as your internship? Join in!
  * [Fill out the interest form](https://docs.google.com/forms/d/e/1FAIpQLSfU-hxUyo7NPuvTTUFwy0J0F2iQn3a6r_5m8WlIoYQBpnTUjQ/viewform) for staying in the loop regarding pune meetups and activities
  * [Join us on Meetup.com](http://www.meetup.com/DataMeet-Pune/)
  * Contact us on email: pune [at] datameet.org 
  * Text Nikhil on [+919665831250](intent://send/+919665831250#Intent;scheme=smsto;package=com.whatsapp;action=android.intent.action.SENDTO;end) and ask to be added to the DataMeet Pune whatsapp group
  * Join the [all-India DataMeet mailing list](https://groups.google.com/forum/#!forum/datameet)
  * Join the [DataMeet slack network](http://datameet.org/wp-login.php?action=slack-invitation) and once in, join the #pune channel.

## The Team
Nikhil: Formerly in the IT sector, Nikhil has graduated from a degree-less alternative university where he self-designed his course with a community of learners from diverse backgrounds. He has multiple interests in technology, sustainability and democracy. His journey with open data started with a project with Centre for Environment Education and since then he has been involved with other voluntary projects and community initiatives. Having a presence in many networks and constantly cross-pollinating developments amongst them, he is keen to work on open data, while recognizing technology’s role as merely a tool and not an end, prioritizing simplicity and stakeholder empowerment.

Craig Dsouza : Craig is a graduate with a Master’s in Environmental Policy from the University of Delaware and currently works at SOPPECOM, Pune in research on rural water related issues. His research involves a substantial amount of data analysis and field work related to agricultural water use, cropping patterns and hydrological data. This exploration drove his curiosity on the subject of data availability & data quality in the social sector in India and consequently to Datameet’s work. He believes grassroots citizen action (which is strengthened by open data and transparency) is the key to overcoming overwhelming challenges to the equitable management of water resources in India.

This page is hosted on Github. [Check out the repo here.](https://github.com/datameet-pune/datameet-pune.github.io/)
