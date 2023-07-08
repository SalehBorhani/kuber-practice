FROM alpine
WORKDIR /app
COPY . .
RUN chmod +x /app/test.sh
ENTRYPOINT [ "./test.sh" ]