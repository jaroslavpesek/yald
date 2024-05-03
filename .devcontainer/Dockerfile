# Use Fedora as the base image
FROM alpine:latest

# Update
RUN apk update

# Install tectonic
RUN apk add --no-cache texlive-full
RUN apk add --no-cache biber
RUN apk add --no-cache git

CMD ["bash"]
