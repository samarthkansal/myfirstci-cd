# Base Image
FROM alpine

# download and install the dependency

RUN add apk --update redis

# Tell the image what to do when starts as a container
CMD["redis-server"]