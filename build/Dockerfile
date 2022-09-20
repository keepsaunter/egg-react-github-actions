FROM node
COPY app-code.zip /origin-app-code.zip
EXPOSE 7001
ENTRYPOINT unzip -d /app-code /origin-app-code.zip && cd /app-code && npm run prod-start