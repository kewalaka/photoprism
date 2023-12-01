FROM golang:1.21.4-alpine3.18

# Q: What is this?
# A: DDNS is a personal DynDNS client for DigitalOcean, see https://github.com/skibish/ddns.

RUN go install github.com/skibish/ddns@latest

CMD ["ddns", "-conf-file", "/config/ddns.yml"]