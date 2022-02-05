FROM ubuntu:20.04
COPY scriptfile.sh .
RUN apt-get update && apt-get install -y curl
ENTRYPOINT ["./scriptfile.sh"]