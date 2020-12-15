
FROM alpine:3.12.2

RUN apk add ruby

RUN echo 'puts "Hello World!"' > helloworld.rb

CMD ["helloworld.rb"]
ENTRYPOINT ["ruby"]
