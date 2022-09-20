FROM node:16
COPY . /app-code
WORKDIR /app-code
RUN npm install --omit=dev
EXPOSE 7001
ENTRYPOINT /bin/bash & npm run prod-start