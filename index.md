# Index

This is the index page in markdown. I'll be building this up with docs and notes.

This is not meant to be a professional site in any way, just a way for me to keep notes and docs together in one place in easy-to-edit markdown files which can be easily published with git.

Tips for publishing markdown files:

- When linking the files, do not use the extension - just use the filename, like `document`, instead of `document.md`
- Use relative paths to links; there is no need to link from the root, like `(../blob/master/docs/doc2)` - this did not work when I tested it
- The syntax for links is `[text](link)`
- Create folders to separate docs, but remember to add an `index.md` page - or you'll see a "page not found" error

It appears that markdown doesn't have a `target="_blank"` feature so that links open in a different tab, so that's a bummer.

I'm going to try using raw html and see if that works.

Here is a link to <a href="http://www.google.com" target="_blank">Google</a>

That appears to work - I won't know until I publish the page - the preview shows a link. But my markdown linter is complaining about inline html (markdownlint MD033)

If it works I'll just have to ignore the warning if I really want certain links to open in a new tab. Or just use inline links and open them in new tabs as needed.
