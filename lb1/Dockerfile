FROM ubuntu:latest
RUN apt-get update
RUN apt-get -y install haproxy
COPY ./haproxy.cfg /etc/haproxy/haproxy.cfg
CMD haproxy -d -f /etc/haproxy/haproxy.cfg
