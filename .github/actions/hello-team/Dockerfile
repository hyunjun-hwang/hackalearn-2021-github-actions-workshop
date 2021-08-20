FROM golang:1.15

WORKDIR /go/src/hello

COPY . .

RUN go get -d -v ./...

RUN go install -v ./...

CMD ["hello"]

#golang을 써서 docker위에 올라갈수있도록
#이 레퍼지토레이있는 코드를 카피해서 가져온다음에
#필요한것들을 인스톨하는 방식으로되어있다