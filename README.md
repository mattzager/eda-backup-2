# app_demo

`podman pull quay.io/acme_corp/eda-app:latest`

`deploy.yml` is used to pull a docker image from Quay that contains `app.py` and `./templates/hello.html`
Some of the attributes of this application can be modified by adjusting variables defined in `deploy.yml`

Variables are defined conditionally based on events from a git provider like Gitea.

The application resides in the `app` directory and can be built with the included Dockerfile.