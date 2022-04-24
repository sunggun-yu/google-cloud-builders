FROM snyk/snyk-iac-rules AS snyk-iac-rules

FROM gcr.io/cloud-builders/docker
COPY --from=snyk-iac-rules /usr/local/bin/snyk-iac-rules /usr/local/bin/snyk-iac-rules

ENTRYPOINT [ "snyk-iac-rules" ]
