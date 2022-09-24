# TwitterToNitter

![illustration](https://raw.githubusercontent.com/no-gravity/TwitterToNitter/main/illu.jpg)
(Illustration by [Jenny from illubots](https://www.instagram.com/illubots/))

A bookmarklet that shows the current Twitter page on Nitter. On every click it, chooses a random Nitter instance:

__javascript:h=['nitter.it','nitter.snopyta.org','nitter.net'];window.location.host=h[Math.floor(Math.random()*h.length)];__

I like Twitter, but I am usually not logged in when I read a tweet. And then Twitter shows a nag screen after a bit of reading, and then I manually change to Nitter. This bookmarklet automates it.

Since Nitter instances are overloaded sometimes, it chooses a random Nitter instance every time you click it.

If you are new to bookmarklets, here is how they work:

If you are using a desktop browser, you can just drag and drop this link to your bookmark bar:

[TwitterToNitter](javascript:h=['nitter.it','nitter.snopyta.org','nitter.net'];window.location.host=h[Math.floor(Math.random()*h.length)];)

On a mobile browser, perform these steps:

- 1: Bookmark some page. It does not matter which one.
- 2: Edit the Bookmark and replace the URL with the "javascript:h=[...]" line above, including the "javascript:", up to the final ";". Give it a nice name.
- 3: It works :) Every time you click the bookmark, it will select a random Nitter instance to show the current tweet.

## Update

Turns out there also is a simple two-click solution to read Twitter when not logged in.

When getting the nag screen, click on "Log in" and then click the "X". Boom! You can continue reading:

https://twitter.com/marekgibney/status/1573625913492869120
