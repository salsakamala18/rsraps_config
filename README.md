

[Deploy to a subdirectory with a Path PrefixJump to heading](https://www.11ty.dev/docs/config/#deploy-to-a-subdirectory-with-a-path-prefix)
## Deploy to a subdirectory with a Path PrefixJump to heading
If your site lives in a different subdirectory (particularly useful with GitHub pages), use pathPrefix to specify this. When paired with the HTML <base> plugin it will transform any absolute URLs in your HTML to include this folder name and does not affect where things go in the output folder.
## Path Prefix

| Status | Response  |
| ------ | --------- |
| Command Line Override    |Some code here:<br><pre>--pathprefix&#13;</pre>|
| 400    |Some text here|

| Status | Response  |
| ------ | --------- |
| 200    |Some code here:<br><pre lang="json">{  "id": 10,  "username": "alanpartridge"}</pre>|
| 400    |Some text here|
