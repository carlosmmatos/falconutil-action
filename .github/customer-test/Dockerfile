# Stand-in for the customer's multi-stage application image (build target "cyber")
FROM debian:12-slim AS base
COPY hello.txt /hello.txt

FROM base AS cyber
CMD ["cat", "/hello.txt"]
