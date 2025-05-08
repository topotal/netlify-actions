FROM node:22-alpine

LABEL version="1.0.4"
LABEL repository="https://github.com/topotal/netlify-actions"
LABEL homepage="https://github.com/topotal/netlify-actions"
LABEL maintainer="topotal"
LABEL "com.github.actions.name"="Topotal"
LABEL "com.github.actions.description"="Wraps the Netlify CLI to enable common Netlify commands"
LABEL "com.github.actions.icon"="cloud"
LABEL "com.github.actions.color"="blue"

RUN npm install -g netlify-cli

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
