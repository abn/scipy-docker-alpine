# Alpine Docker Image for SciPy

This image provides a lightweight (note this is used loosely when compared to the based image) runtime environment for SciPy codebases. This is an interim measure while the `py-numpy`, `py-matplotlib` and `py-scipy` available via the `@community` and `@testing` repositories are unstable. Alternatively, this allows for the latest version of these packages to be used before they are available in the main repository.

This image is constructed using the latest alpine base image at the time of build.

## Usage
```sh
docker run --rm -it alectolytic/scipy:latest python
```
