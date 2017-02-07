FROM ubuntu:16.04
ENV PYTHONUNBUFFERED 1

RUN apt-get update && apt-get install -y \
  build-essential \
  python3 \
  python3-pip \
  python3-dev \
  ipython \
  git-core \
  libpq-dev \
  libjpeg-dev \
  binutils \
  libproj-dev \
  gdal-bin \
  libxml2-dev \
  libxslt1-dev \
  zlib1g-dev \
  libffi-dev \
  libssl-dev \
  language-pack-pt

RUN dpkg-reconfigure locales
# Set the locale
RUN locale-gen en_US.UTF-8
ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8
ENV LC_CTYPE en_US.UTF-8
RUN locale


