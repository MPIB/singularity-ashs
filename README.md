# singularity-ashs
Singularity recipes for base-images containing ashs.

 - ashs is pulled from its [github repository](https://github.com/pyushkevich/ashs).
 - Its dependencies are installed through the debian repositories via `apt-get install`.
 - At the end of the build process the image is cleaned up by:
    - removing installation dependencies through `apt-get purge`,
    - deleting the package cache,
    - deleting the git repositories history.