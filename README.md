## Build
`docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:4 jekyll build`

## Startup  
`docker run --name blog -p 8080:80 -v $PWD:/usr/share/nginx/html:ro -d nginx`

## Access

http://localhost:8080/