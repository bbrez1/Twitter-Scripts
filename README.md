# Twitter-Scripts



**Script: Unfollow everyone who doesn't follow me back**

Usage: 

- Go to https://twitter.com/following
- Scroll down
- Open console and paste the below script

```
$(".ProfileCard-content:not(:contains('follows you'))").each(function(index) { $(this).find('.user-actions-follow-button').click(); });
```

- Wait until the script finishes. 
- IMPORTANT: If you want to repeat the process then refresh the page (otherwise the script will refollow everyone once you run it again).
