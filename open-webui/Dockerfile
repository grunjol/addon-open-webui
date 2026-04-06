ARG BUILD_FROM=ghcr.io/open-webui/open-webui:0.8.12-ollama
FROM $BUILD_FROM

COPY run.sh /
RUN chmod a+x /run.sh
CMD [ "/run.sh" ]

LABEL \
  org.opencontainers.image.title: "Open WebUI Home Assistant Addon" \
  org.opencontainers.image.description: "Open WebUI is an extensible, self-hosted interface for AI that adapts to your workflow, all while operating entirely offline." \
  org.opencontainers.image.source="https://github.com/grunjol/addon-open-webui"


