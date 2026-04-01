# Dockerfile for C++ backend
FROM alpine:latest
RUN apk add --no-cache g++ make sqlite-dev
WORKDIR /app
COPY backend /app
RUN g++ main.cpp -o app -lsqlite3
CMD ["./app"]
