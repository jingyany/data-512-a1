# Analyzing Monthly Traffic of English Wikipedia

## Project Goal

The goal of this project is to constract, analyze, and publish a dataset of monthly traffic on English Wilipedia from July 1 2008 throught September 30 2017.

## Data

#### The License of the Source Data

[Text of CC BY-SA 3.0 Unported License](https://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License)

[Text of CC BY-SA 4.0 International License](https://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_4.0_International_License)

[Text of the GFDL](https://en.wikipedia.org/wiki/Wikipedia:Text_of_the_GNU_Free_Documentation_License)

#### The Wikimedia Foundation Terms of Use

https://wikimediafoundation.org/wiki/Terms_of_Use/en)


## Relevant API Documentation

The legacy Pagecounts API provides access to desktop and mobile traffic data from January 2008 through July 2016.
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts

The Pageviews API provides access to desktop, mobile web, and mobile app traffic data from July 2015 through September 2017.
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

## Final Data Desciption

The final data file generated for data analysis contains eight variables(columns). They are listed below:

- year: the year of the monthly traffic
- month: the month of the monthly traffic
- pagecount_all_views: the monthly pagecount of total views, include desktop view and mobile views.
- pagecount_desktop_views: the monthly pagecount of desktop view.
- pagecount_mobile_views: the monthly pagecount of mobile view.
- pageview_all_views: the monthly pageview of total views, include desktop view and mobile views.
- pageview_desktop_views: the monthly pageview of desktop view.
- pageview_mobile_views: the monthly pageview of mobile view.

## Other Information

- The data from the Pageview API exludes priders/crawlers, while data from the Pagecounts API does not.
- The data from the Pageview API only available from July 2015 to September 2017, while data of the Pagecounts API is available from January 2008 to July 2016.

## Licence

The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology (MIT). As a permissive license, it puts only very limited restriction on reuse and has therefore an excellent license compatibility. For detailed description of the contents of license please refer to the file [License](https://github.com/jingyany/data-512-a1/blob/master/LICENSE).
