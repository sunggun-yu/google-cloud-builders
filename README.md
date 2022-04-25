# Google cloud builder docker images

## Publish builder

run `cloud builds submit` command

example:

```bash
cd snyk-cli
gcloud builds submit --config cloudbuild.yaml .
```

or,

```bash
gcloud builds submit --config snyk-cli/cloudbuild.yaml snyk-cli
```
