## podcast-dl-mixcloud

CLI to easily download podcast(s) from mixcloud.


### install

```shell
npm i podcast-dl-mixcloud
cd ./node_modules/podcast-dl-mixcloud
```


### usage

```shell
node index.js [user] [podcast_id (or space-separated list of podcast_ids)]
```

*e.g. to download 3 podcasts from Resident Advisor*:  
```node index.js residentadvisor ra105 ra335 ra442```

### dev notes

consider this code as __alpha__ quality, it relies upon some regexp matching of HTML text which could easily break


### license

MIT