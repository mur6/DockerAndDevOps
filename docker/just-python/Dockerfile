FROM python:3-stretch

RUN apt-get update && apt-get install -y --no-install-recommends \
        locales && \
    rm -rf /var/lib/apt/lists/* && \
    apt-get clean && \
    echo "ja_JP.UTF-8 UTF-8" > /etc/locale.gen && \
    locale-gen ja_JP.UTF-8
