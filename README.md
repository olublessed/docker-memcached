[![](https://images.microbadger.com/badges/image/babim/memcached.svg)](https://microbadger.com/images/babim/memcached "Get your own image badge on microbadger.com")[![](https://images.microbadger.com/badges/version/babim/memcached.svg)](https://microbadger.com/images/babim/memcached "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/babim/memcached:pass.svg)](https://microbadger.com/images/babim/memcached:pass "Get your own image badge on microbadger.com")[![](https://images.microbadger.com/badges/version/babim/memcached:pass.svg)](https://microbadger.com/images/babim/memcached:pass "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/babim/memcached:alpine.svg)](https://microbadger.com/images/babim/memcached:alpine "Get your own image badge on microbadger.com")[![](https://images.microbadger.com/badges/version/babim/memcached:alpine.svg)](https://microbadger.com/images/babim/memcached:alpine "Get your own version badge on microbadger.com")

# About this Repo

This is the Git repo of the Docker [official image](https://docs.docker.com/docker-hub/official_repos/) for [memcached](https://registry.hub.docker.com/_/memcached/). See [the Docker Hub page](https://registry.hub.docker.com/_/memcached/) for the full readme on how to use this Docker image and for information regarding contributing and issues.

The full readme is generated over in [docker-library/docs](https://github.com/docker-library/docs), specificially in [docker-library/docs/memcached](https://github.com/docker-library/docs/tree/master/memcached).

See a change merged here that doesn't show up on the Docker Hub yet? Check [the "library/memcached" manifest file in the docker-library/official-images repo](https://github.com/docker-library/official-images/blob/master/library/memcached), especially [PRs with the "library/memcached" label on that repo](https://github.com/docker-library/official-images/labels/library%2Fmemcached). For more information about the official images process, see the [docker-library/official-images readme](https://github.com/docker-library/official-images/blob/master/README.md).

[![Travis CI](https://img.shields.io/travis/docker-library/memcached/master.svg)](https://travis-ci.org/docker-library/memcached/branches)

```
docker run -it -p 11211:11211 -d babim/memcached:alpine
```
