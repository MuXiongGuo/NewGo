FROM golang:latest

ENV GOPROXY https://goproxy.cn,direct
WORKDIR D:/NewGo/go-gin-example
COPY . D:/NewGo/go-gin-example
RUN go build .

EXPOSE 8000
ENTRYPOINT ["./go-gin-example"]