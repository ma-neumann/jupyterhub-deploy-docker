ARG DOCKER_NOTEBOOK_IMAGE
FROM $DOCKER_NOTEBOOK_IMAGE
ARG JUPYTERHUB_VERSION
RUN python3 -m pip install --no-cache jupyterhub==$JUPYTERHUB_VERSION
RUN python3 -m pip install --no-cache ipython-sql
LABEL com.centurylinklabs.watchtower.enable=false
