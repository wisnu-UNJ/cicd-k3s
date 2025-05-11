FROM bitnami/kubectl:latest

USER root
COPY ca.crt /usr/local/share/ca-certificates/gitlab.crt
RUN update-ca-certificates
RUN apt install docker.io -y
CMD ["sh"]
