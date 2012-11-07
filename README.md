# Knockout, in npm

This is a straight-up port of the latest debug build of Knockout into an npm package. Since Knockout already exports
itself as a Node.js module, there is no need to modify the source in any way.

Recommended for use with [Browserify][] or other tools that allow you to use CommonJS-style modules directly in the
browser.

---

Q: Why isn't this package simply named "knockout"?

A: Someone [took that name][] and put a wierd version of Knockout on npm, gummed up with some jsdom stuff. Annoying.

[Browserify]: https://npmjs.org/package/browserify
[took that name]: https://npmjs.org/package/knockout
