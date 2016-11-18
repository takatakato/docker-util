# jsonlint & jsondiffpatch
# docker run --rm -v  $(pwd):/work takatakato/util {jsonlint | jsondiffpatch } ${JSON_FILE}

FROM alpine:3.4

RUN apk --no-cache add nodejs \
	&& npm install -g jsonlint \
	&& npm install -g jsondiffpatch

WORKDIR /work