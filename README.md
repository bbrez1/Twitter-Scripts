# Twitter-Scripts



**Script: Unfollow everyone who doesn't follow me back**

Usage: 

1. Go to https://twitter.com/following
 
2. Scroll down
 
3. Open console and paste the below script

```
$(".ProfileCard-content:not(:contains('follows you'))").each(function(index) { $(this).find('.user-actions-follow-button').click(); });
```

4. Wait until the script finishes. 

IMPORTANT: If you want to repeat the process then refresh the page (otherwise the script will refollow everyone once you run it again).
