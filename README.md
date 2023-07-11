# GU WordPress assets

This repository contains any assets or static media files for use in WordPress administration and testing.

## RSS feeds

The following RSS feeds are housed in this repository:

* __Dashboard Announcements__ (updated as needed and displayed on the WP admin dashboard)
* __Test Content__ (static, for use in automated testing)
* __Test Content, single__ (static, for use in automated testing)

### Feed items

Each item in an RSS feed has the following structure:

```
<item>
  <title>TITLE GOES HERE</title>
  <link>https://uis.georgetown.edu</link>
  <pubDate>Tue, 31 Jul 2018 01:01:01 EDT</pubDate>
  <description>
    <![CDATA[
      CONTENT GOES HERE. <em>HTML OPTIONAL.</em>
    ]]>
  </description>
  <enclosure url="IMAGE_URL_HERE.JPG" length="###" type="image/jpeg" />
</item>
```
