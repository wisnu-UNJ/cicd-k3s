FROM bitnami/kubectl:latest

USER root
COPY ca.crt /usr/local/share/ca-certificates/gitlab.crt
RUN update-ca-certificates
CMD ["sh"]
