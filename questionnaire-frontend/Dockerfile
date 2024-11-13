FROM node:12
WORKDIR /app
COPY . .
RUN npm install && npm run build
CMD ["npx", "http-server", "dist/questionnaire-backend", "-p", "8080"]
EXPOSE 8080