FROM google/golang

MAINTAINER genzj

WORKDIR /shadowsocks-config
RUN go get github.com/shadowsocks/shadowsocks-go/cmd/shadowsocks-server

EXPOSE 8388

ENTRYPOINT ["shadowsocks-server", "-c", "config.json"]
