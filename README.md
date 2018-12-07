# qb.js

![screenshot](https://raw.github.com/smhanov/qb.js/master/assets/screenshot.png)

A QBASIC implementation in JavaScript. 

Because it uses AJAX to retrieve the .BAS file, you cannot run it using a file:/// url in most browsers. You have to start an http server to run it. (python -m SimpleHTTPServer is a quick one)

You can read the blog post about the library at [stevehanov.ca/blog/index.php?id=92](http://stevehanov.ca/blog/index.php?id=92).

WARNING WARNING I only implemented enough of the language to run NIBBLES.BAS! It probably won't run your program and my parser makes it difficult to debug what is wrong. I think it would take several years of effort to do the whole language. This is not worth mine or anybody's effort, since you can run the real QBASIC in a javascript dosbox emulator these days... (for example https://js-dos.com/)

If I were doing it again, I would replace the parser with a packrat parser such as peg.js.

Copyright 2014 Steve Hanov

Licensed GPL v3, see the LICENSE file.
