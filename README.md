```
export JEKYLL_VERSION=3.8; docker run --rm   -p 4000:4000 --volume="$PWD:/srv/jekyll"   -it jekyll/jekyll:$JEKYLL_VERSION   jekyll serve
```
```
instructions for Windows powershell
cd Documents\GitHub\wedding-website-2\wedding-website
docker run --rm   -p 4000:4000 --volume="${PWD}:/srv/jekyll"   -it jekyll/jekyll:3.8   jekyll serve
```
