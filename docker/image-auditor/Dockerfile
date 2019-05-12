FROM node:4.3.1

WORKDIR /opt/app/

COPY src /opt/app/
RUN npm install
COPY src/auditor.js /opt/app/auditor.js

EXPOSE 2205

ENTRYPOINT ["node", "/opt/app/auditor.js"]