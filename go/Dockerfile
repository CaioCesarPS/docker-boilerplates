FROM golang:1.23

WORKDIR /app

# COPY go.mod go.sum ./
# RUN go mod download && go mod verify

COPY . .
# RUN go build -v -o main .

CMD ["tail", "-f", "/dev/null"]