FROM homebrew/brew AS brew
RUN brew install snyk/tap/snyk

FROM gcr.io/cloud-builders/docker
COPY --from=brew /home/linuxbrew/.linuxbrew/bin/snyk /usr/local/bin/snyk

ENTRYPOINT [ "/usr/local/bin/snyk" ]
