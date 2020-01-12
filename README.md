# lncm/docker-base

This repo can be used as a template for creating new LNCM-style images:

* **Reproducible** - whenever possible binaries are build in a way anyone can replicate arriving at binaries that are bitwise identical 
* **Automated** - `git-push` triggers build, which if successful deploys images to Docker Hub & Github Releases
* **Auditable** - each step of the process prints relevant environment info, as well as details about built binaries
* **Multi-architecture** - each Docker image is provided for at least: `amd64`, `arm64`, `arm32v7`, and `arm32v6`
* **Unopinionated** - all images are built in the most general way possible, allowing their extension to suit anyone's needs
* **Minimal** - all images strive to be as small as possible
* **Simple** - all `Dockerfiles` strive to be well documented, and easy to follow
* **Convenient** - all images follow similar conventions, and all conventions are chosen to be as expected & intuitive as possible
    * **`USER`** - all images are run as _`user`_ (named the same as the software within)
    * **`TODO`** - write the rest 😅
    
