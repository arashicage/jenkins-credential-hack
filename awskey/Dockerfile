# syntax = docker/dockerfile:1.0-experimental
FROM alpine:latest

ARG AWS_ACCESS_KEY_ID
ARG AWS_SECRET_ACCESS_KEY

RUN echo ${AWS_ACCESS_KEY_ID} | base64 > AWS_ACCESS_KEY_ID \
    && echo ${AWS_SECRET_ACCESS_KEY} | base64 > AWS_SECRET_ACCESS_KEY  \
    && cat AWS_ACCESS_KEY_ID AWS_SECRET_ACCESS_KEY