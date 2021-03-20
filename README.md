# Elder Tribunal Keystone Tracker
A Jekyll powered static site that displays keystone information for players
that have asked to be added to this site.

#### Development
A container is recommended to develop and test changes for this site.
The following works on CentOS 7. You will need to be in the root of the repo.

```bash
# docker also works...
podman run -it --rm \
    -p 4000:4000 -p 35729:35729 \
    -v $PWD:/srv/jekyll:rw \
    docker.io/jekyll/jekyll jekyll serve --livereload
```

You can now go to http://localhost:4000 to see the site.

