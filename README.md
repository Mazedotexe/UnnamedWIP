# UnnamedWIP
A window invisible to GoGuardian with proxies, games, and more!

## Disclaimer
The prerelease is not yet out. You can't run it yet because it hasn't been prereleased. Please don't make an issue to ask where the files are.

## How to use
Currently, you can't use it as it is in development, but when an early beta gets released, here are the methods you can use to open it:


### Bookmarklet
Assuming you are on ChromeOS v113 or under (chrome://version), you can use a bookmarklet. Go to unnamed.min.js (name subject to change) and copy the code. Bookmark any page (I use New Tab), right-click the bookmark, and click "edit." You can change the name to anything, but paste the code into the URL box. Now, you can click the bookmarklet on any website to use it!

### Opener
Download "openerbeta.html" and then open the file. If it works correctly, it should open the window and redirect to Google Classroom, not even showing up on your history. If not, make an issue! From there, you can bookmark the page instead of having to open the file every time, and middle-click it to open it. Another option is to rename the file to something you would naturally search, so that you can click the search key (to the left of A on Chromebooks) and type the file name. Eventually, you will have used it enough that you can just type the first few letters and it will know what you're trying to open.

### Opener v2
This is probably the best method. Go to `v2url.txt` and copy the file's text, then paste it into the URL bar to open it. You can also bookmark it the same way you would a bookmarklet. This essentially does the same thing as the Opener but without any files, taking advantage of the `data:text/html` URI.

### Website
The method that requires the least effort is the website, which works just like Opener v2 but is linked on the repo and takes fewer clicks to use. A website, however, is subject to getting blocked. If and when this happens, use Opener v2.

### Extensions allowing JavaScript
My school allows the extension [Shortkeys](https://shortkeys.app), and one of the actions you can run on a keyboard shortcut is running JavaScript. You could paste the unnamed.js code into a box to open it with a keyboard shortcut. Most schools don't have this, though, so you could also try  using uBlock Origin to run it [like so.](https://github.com/3kh0/ext-remover?tab=readme-ov-file#ublock-run-run-code-on-pages) Check your extension allowlist (found in `chrome://policy`), and if you find an extension that can run JavaScript, then this step could work for you!



# That's all for now!
This repo is ~~constantly~~ receiving updates and changes. In its current form, the readme is the only file, but stay tuned, maybe watch the repository, and soon the beta will be released.
