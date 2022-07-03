FROM alpine
RUN apk add python3

# setup web server
COPY index.html /web/index.html
WORKDIR /web
CMD python3 -m http.server 8000
