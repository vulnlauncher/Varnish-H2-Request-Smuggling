FROM alpine:latest
RUN apk add --no-cache nmap-ncat
ENTRYPOINT ["ncat"]
CMD ["-kl", "80"]
