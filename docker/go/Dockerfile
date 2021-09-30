FROM golang:latest
RUN mkdir /go/src/app
WORKDIR /go/src/app
ADD . /go/src/app
# golang version 1.17 is using go install.(not use go get)
#ホットリロード機能
# RUN go get -u github.com/cosmtrek/air
# CMD ["air", "-c", ".air.toml"]