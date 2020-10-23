FROM node:4-slim
WORKDIR /app
RUN npm install express
RUN npm install redis
COPY files/ /files/
COPY webui.js /

ENTRYPOINT ["node"]
CMD ["webui.js"]
EXPOSE 8080
