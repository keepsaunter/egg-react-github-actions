FROM node
COPY app-code.zip /origin-app-code.zip
EXPOSE 7001
CMD unzip -d /app-code /origin-app-code.zip && cd /app-code && npm run prod-start
ENTRYPOINT /bin/bash