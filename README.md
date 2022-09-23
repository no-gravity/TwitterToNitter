# TwitterToNitter
Bookmarklet that shows the current Twitter page on Nitter. On every click it, chooses a random Nitter instance.

javascript:h=['nitter.it','nitter.snopyta.org','nitter.net']; location.href=location.href.replace(window.location.host,h[Math.floor(Math.random()*h.length)]);

I like Twitter, but I am usually not logged in when I read a tweet. And then Twitter shows a nag screen after a bit of reading, so I usually manually change to Nitter. This bookmarklet automates it.

Since Nitter instances are overloaded sometimes, it chooses a random Nitter instance every time you click it.
