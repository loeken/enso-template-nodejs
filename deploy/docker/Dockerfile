FROM loeken/enso-template-base

# install nodejs/npm/pnpm
RUN apk add --no-cache nodejs npm
RUN npm install -g pnpm

# switch to non root user
USER vscode
WORKDIR /app

CMD ["tail", "-f", "/dev/null"]
