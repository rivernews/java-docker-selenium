# https://github.com/SeleniumHQ/docker-selenium#running-the-images

# To inspect visually what the browser is doing use the standalone-chrome-debug
FROM selenium/standalone-chrome-debug:3.141.59-zinc

# you can also run this container directly with the command below
# 
# use shm-size = 2g
#
# docker run --rm -p 4444:4444 -p 5900:5900 --shm-size 2g selenium/standalone-chrome-debug:3.141.59-zinc bash -c ". /opt/bin/entry_point.sh"
#
# or use host's /dev/shm
# docker run --rm -p 4444:4444 -p 5900:5900 -v /dev/shm:/dev/shm selenium/standalone-chrome-debug:3.141.59-zinc bash -c ". /opt/bin/entry_point.sh"




# if you don't need to see what the browser is doing, use this image:
FROM selenium/standalone-chrome:3.141.59-zirconium
# you can also run this container directly with the command below
#
# use host's /dev/shm
#
# $ docker run -d -p 4444:4444 -v /dev/shm:/dev/shm selenium/standalone-chrome:3.141.59-zirconium
#
# or use shm-size = 2g
#
# $ docker run -d -p 4444:4444 --shm-size=2g selenium/standalone-chrome:3.141.59-zirconium