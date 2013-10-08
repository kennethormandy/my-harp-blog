# A Simple Article

I’ve always enjoyed pretending to be a developer. Faking my way through new web technologies has become a familiar exercise. This time was different. The deception didn’t come from me, but my own development environment. I was using preprocessors to translate markup and code into something more common. Preprocessors make HTML & CSS much more capable. Repeatedly arranging them, however, didn’t make _me_ feel more capable.

Still, they are so useful, I continued working however they demanded. As I understood it, continually compiling my preprocessed code down to HTML, CSS & JavaScript was necessary for every project. I thought it was just how preprocessing worked—but it’s not.

This was in the back of my mind when I first tried [Harp](http://harpjs.com), the static web server with built-in preprocessing. Support for Markdown, Jade, LESS, Stylus, and more are all present. With Harp, the compiled HTML, CSS & JavaScript files aren’t tossed back into my project—I don’t need them there. Instead, as I make changes, they are delivered where they actually need to be: the browser.