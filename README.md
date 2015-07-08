# docker-openstf-base

This is the [Docker](https://www.docker.com/) base image for [openstf/stf](https://registry.hub.docker.com/u/openstf/stf). It's main purpose is to speed up build time, especially since the official [Docker Hub](https://hub.docker.com/) doesn't cache layers. What sets it apart from the [official Node.js images](https://registry.hub.docker.com/u/library/node/) is that it's especially suited for building native extensions (sources needed by `node-gyp` are prefetched) and comes with a bit less bloat.

Additionally, native libraries and tools required by [STF](https://github.com/openstf/stf) are installed here to further reduce build and pull times.

## License

See [LICENSE](LICENSE).

Copyright © CyberAgent, Inc. All Rights Reserved.
