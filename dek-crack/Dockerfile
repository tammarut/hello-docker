# Use a existing docker image as base
FROM alpine
LABEL maintainer="foo"
# Download and install a dependency
RUN apk add --update redis
# Start
CMD ["redis-server"]
