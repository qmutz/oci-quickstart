FROM golang:1.22.4

LABEL "name"="Create Image"
LABEL "version"="1.0"

COPY marketplace_image.json /
COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]
