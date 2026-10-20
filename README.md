# ffmpeg-builds

Pinned static builds of ffmpeg, kept so Jack's container images do not depend on the upstream host being up at build time.

Each release is one upstream version, its tarballs unchanged, with a `SHA256SUMS` beside them. The Dockerfiles fetch a release asset by version and check the sum; a version is never floated.

- `ffmpeg-7.0.2`: John Van Sickle's static Linux builds, https://johnvansickle.com/ffmpeg/, every architecture the site publishes.
