#
# Copyright 2021-2023 FLECS Technologies GmbH

ARG ARCH
ARG VERSION
ARG VARIANT

FROM eclipse-mosquitto:${VERSION}

ARG ARCH
ARG VERSION
ARG VARIANT

RUN [ ! -z "${ARCH}" ]
RUN [ ! -z "${VERSION}" ]

ADD docker/fs/ /
