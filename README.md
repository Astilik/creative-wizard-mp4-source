# Creative Wizard Suite — MP4 encoder source package

Creative Wizard Suite includes the web build from `h264-mp4-encoder@1.0.12`. This source package preserves the upstream `v1.0.12` source tree, its build scripts, and the two submodules pinned by that tag. It is provided for source availability and license transparency; it does not license the proprietary Creative Wizard Suite code.

| Component | Revision | License |
| --- | --- | --- |
| [h264-mp4-encoder](https://github.com/TrevorSundberg/h264-mp4-encoder/tree/v1.0.12) | `6d177fd043157606224cef4702e134dd31f6adfa` | MIT wrapper |
| [libmp4v2](https://github.com/TrevorSundberg/libmp4v2/tree/d49b4466ed76fc23b59e31a5f7f10f34b30ad7c4) | `d49b4466ed76fc23b59e31a5f7f10f34b30ad7c4` | MPL 1.1 |
| [minih264](https://github.com/TrevorSundberg/minih264/tree/25f441086ac8f2eef1c883476c095f9397843ac8) | `25f441086ac8f2eef1c883476c095f9397843ac8` | CC0 |

Public release: [MP4 encoder source for Creative Wizard Suite (v1.0.12)](https://github.com/Astilik/creative-wizard-mp4-source/releases/tag/h264-mp4-encoder-v1.0.12-cw1).

Download the [source archive with pinned submodules](https://github.com/Astilik/creative-wizard-mp4-source/releases/download/h264-mp4-encoder-v1.0.12-cw1/h264-mp4-encoder-v1.0.12-source-with-submodules.tar.gz) (`h264-mp4-encoder-v1.0.12-source-with-submodules.tar.gz`, SHA-256 `14a0df167d2e22318430e725704b4a57ef5cd9448e6442c7c84d44ec7b6518df`). GitHub displays this same digest on the published release asset. The archive excludes Git metadata and includes upstream source, license texts, Dockerfile and build scripts. The upstream package tag's commit matches npm's `gitHead` for version 1.0.12; the npm tarball's web JavaScript is byte-identical to the dependency bundled by Creative Wizard Suite. A C/C++→WASM rebuild has **not** been independently reproduced.

This README indexes the published source package, not proof of license clearance. Keep the archive accessible to plugin recipients and review license obligations and the delivered notice before the paid Suite is submitted to Figma.
