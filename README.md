To build an image with docker:

cd createimage

docker build -t="createimage" .

Then to run that image and attach to it at the same time:

docker run -i -t createimage

Or to run it in the background

docker run -d createimage
