FROM phusion/baseimage:0.10.0

# Use baseimage-docker's init system.
CMD ["/sbin/my_init"]

# ...put your own build instructions here...

RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
