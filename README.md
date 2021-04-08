Oh, that's just my [landing page](https://howanski.github.io) code container

To test locally in docker: 
docker run --rm -p 4000:4000 --volume="${PWD}:/srv/jekyll" --volume="${PWD}/vendor/bundle:/usr/local/bundle" -it jekyll/jekyll jekyll serve

Gemfile.lock update:
docker run --rm --volume="${PWD}:/srv/jekyll" -it jekyll/jekyll bundle update
