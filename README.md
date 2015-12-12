# alpine_webkit2png

A lean Alpine Linux Docker image with webkit2png + deps and modified xvfb-run to work on Alpine.

# Usage

docker pull cjpetrus/alpine_webkit2png
docker run -it cjpetrus/alpine_webkit2png bash

webkit2png -g 1000 1000 -x 1280 1024 --aspect-ratio keep -w 4 --output /tmp/google_ss.png http://www.google.com
