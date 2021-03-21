# build-config
HackGT's version controlled Cloud Build configuration template

## How to use:

**If the repo is public:**

1. Copy the contents of `cloudbuild.yaml` to your repository

**If the repo is private:**

1. Copy the contents of `cloudbuild-secret.yaml` to your repository, and rename to `cloudbuild.yaml`

Then,

2. Modify your `Dockerfile` as needed, using Ehsan and/or [the Docker documentation](https://docs.docker.com/develop/develop-images/multistage-build/#use-multi-stage-builds) as an example

## FAQ

### My build is timing out, what do I do?
You can increase the allowed time for a build by editing the `timeout` field and increasing the number of seconds.
