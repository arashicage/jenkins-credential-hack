# syntax = docker/dockerfile:1.0-experimental
FROM alpine

# shows secret from default secret location:
# RUN --mount=type=secret,id=SSHPublicKey cat /run/secrets/mysecret

# shows secret from custom secret location:
RUN --mount=type=secret,id=SSHPublicKey,dst=/foo cat /foo

RUN cat /foo