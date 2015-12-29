## podcast-dl-mixcloud

CLI to easily download podcast(s) from mixcloud.


### install

```shell
npm i podcast-dl-mixcloud
cd podcast-dl-mixcloud
```


### usage

```shell
node index.js [user] [podcast_id (or space-separated list of podcast_ids)]
```


### internals

this code uses data-streaming direct to file & promises, so it should be both efficient (as fast as your connection will allow) and any errors should be captured and reported without halting the process.


### license

MIT