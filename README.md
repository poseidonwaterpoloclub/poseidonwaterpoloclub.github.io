# Poseidons 

## Contribute 

```bash 
ocker run  -ti -w /opt/poseidon -v $PWD:/opt/poseidon -v $PWD/vendor/bundle:/usr/local/bundle --name poseidon -p 4000:4000 jekyll/jekyll bash
jekyll serve
```

