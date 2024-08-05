# Path Prefix
### Deploy to a subdirectory with a Path PrefixJump to heading [here](https://www.11ty.dev/docs/config/#deploy-to-a-subdirectory-with-a-path-prefix)
If your site lives in a different subdirectory (particularly useful with GitHub pages), use pathPrefix to specify this. When paired with the HTML <base> plugin it will transform any absolute URLs in your HTML to include this folder name and does not affect where things go in the output folder.
| Object Key | Default | Command Line Override |
| --- | --- |
| pathPrefix | / |<pre lang="json">--pathprefix</pre>|

