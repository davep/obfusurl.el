[![MELPA](https://melpa.org/packages/obfusurl-badge.svg)](https://melpa.org/#/obfusurl)

# obfusurl.el

`obfusurl.el` provides `obfusurl`, a command that will obfuscate an URL
under the cursor. This might be useful if you are writing out an URL for
someone but the URL itself might spoil the surprise.

For example, this:

`<URL:http://www.davep.org/emacs/>`

is turned into this:

`<URL:http://www.davep.org/%65%6d%61%63%73/>`

The latest obfusurl.el is always available from:

```
   <URL:https://github.com/davep/obfusurl.el>
   <URL:https://github.com/%64%61%76%65%70/%6f%62%66%75%73%75%72%6c%2e%65%6c>
```

Thanks:

Andy Sawyer <andys@morebhp.com> for initially pointing out that URLs with
percent escapes already in them would get broken.

Kevin Rodgers <kevinr@ihs.com> for suggesting a method of fixing the above.

Toby Speight <streapadair@gmx.net> for pointing out that I needed to cater
for reserved characters.
