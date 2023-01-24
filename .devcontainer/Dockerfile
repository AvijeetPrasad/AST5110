ARG VARIANT="16-buster"
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-${VARIANT}
RUN apt-get update && bash /tmp/library-scripts/github-debian.sh
