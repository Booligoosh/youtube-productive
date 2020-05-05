# YouTube Productive
Watch YouTube videos on an alternate domain to distinguish to productivity trackers (Motion, TimeYourWeb, etc.)
---
## Bookmarklet
Add this URL to your bookmarks bar. Then, when you click on the bookmark, it will open the current YouTube video in YouTube Productive.
```
javascript:if(location.host=='www.youtube.com')location.href=`https://youtube-productive.ethan.link/watch?v=${new URLSearchParams(location.search).get('v')}`
```
