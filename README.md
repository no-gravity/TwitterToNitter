# TwitterToNitter
Bookmarklet that shows the current Twitter page on Nitter. On every click it, chooses a random Nitter instance.

javascript:h=['nitter.it','nitter.snopyta.org','nitter.net']; location.href=location.href.replace(window.location.host,h[Math.floor(Math.random()*h.length)]);

I like Twitter, but I am usually not logged in when I read a tweet. And then Twitter shows a nag screen after a bit of reading, and then I manually change to Nitter. This bookmarklet automates it.

Since Nitter instances are overloaded sometimes, it chooses a random Nitter instance every time you click it.

If you are new to bookmarklets, here is how they work:

1: Bookmark some page. It does not matter which one.
2: Edit the Bookmark and replace the URL with the "javascript:h=[...]" line above, including the "javascript:", upt to the final ";".
3: It works :) Every time you click the bookmark, it will select a random Nitter instance to show the current tweet.
