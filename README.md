# GU WordPress assets

This repository contains any assets or static media files for use in WordPress administration and testing.

## RSS feeds

The following RSS feeds are housed in this repository:

* __Dashboard Announcements__ (updated as needed and displayed on the WP admin dashboard)
* __Test Content__ (static, for use in automated testing)
* __Test Content, single__ (static, for use in automated testing)

### Feed items

Each item in an RSS feed has the following structure:

```xml
<item>
  <title>TITLE GOES HERE</title>
  <link>https://uis.georgetown.edu</link>
  <date>Tue, 31 Jul 2018 01:01:01 EDT</pubDate>
  <description>
    <![CDATA[
      CONTENT GOES HERE. <em>HTML OPTIONAL.</em>
    ]]>
  </description>
</item>
```
## Changelog

### 2025-01-24
* older XML `<item>` entities included `<pubDate>`; this has been renamed to `<date>`. 
