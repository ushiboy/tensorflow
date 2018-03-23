# Build for Raspberry PI B Plus's Python 3.5

```
$ CI_DOCKER_EXTRA_PARAMS="-e CI_BUILD_PYTHON=python3 -e CROSSTOOL_PYTHON_INCLUDE_PATH=/usr/include/python3.5" tensorflow/tools/ci_build/ci_build.sh PI-PYTHON3.5 tensorflow/tools/ci_build/pi/build_raspberry_pi.sh PI_ONE
```
