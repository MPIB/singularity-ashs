# singularity-ashs
[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/697)

Singularity recipes for base-images containing ASHS (Automatic Segmentation of Hippocampal Subfields).

 - ASHS is pulled from its [github repository](https://github.com/pyushkevich/ashs).
 - Its dependencies are installed through the debian repositories via `apt-get install`.
 - At the end of the build process the image is cleaned up by:
    - removing installation dependencies through `apt-get purge`,
    - deleting the package cache,
    - deleting the git repositories history.
