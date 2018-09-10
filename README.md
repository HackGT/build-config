# build-config
HackGT's version controlled Cloud Build configuration template

## How to use:

**If your project doesn't have a Docker build step:**

1. Copy the contents of `cloudbuild.tmpl.yaml` to your repository, but save it as `cloudbuild.yaml`

**If your project uses Docker build step(s):**

1. Follow step #1 above for projects without a Docker build step(s)
2. Modify your `Dockerfile` as needed, using Ehsan and/or [the Docker documentation](https://docs.docker.com/develop/develop-images/multistage-build/#use-multi-stage-builds) as an example
