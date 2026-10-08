# NAI Studio dictionary

Optional main tag dictionary downloaded by NAI Studio after the user chooses to install it. No application code or personal data is hosted here.

- `danbooru.sqlite.gz`: 330,745 entries, compressed SQLite database with its search index (about 38 MB download, 79 MB extracted).
- `danbooru-manifest.json`: schema, extracted size and SHA-256 checked before activation.
- `ffdkj-LICENSE.txt`: upstream MIT license.

Source: [ffdkj-Danbooru_Tag-Chinese-English-Translation-Table](https://github.com/ffdkj/ffdkj-Danbooru_Tag-Chinese-English-Translation-Table). The indexed database is derived from the owner's supplied `tag.sqlite`.

Applications pin a repository commit and the database checksum. A completed download is reused offline; incomplete or invalid downloads are never activated.
