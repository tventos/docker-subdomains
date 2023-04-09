FROM node:18.15

WORKDIR /server
COPY .. /server/

# Install Yarn
RUN npm install -g --force yarn

# Install deps
RUN yarn

# Build
RUN yarn build

EXPOSE 3000

# Start
CMD yarn start:prod