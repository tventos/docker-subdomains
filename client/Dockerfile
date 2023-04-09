FROM node:18.15
WORKDIR /client
COPY . /client/

# Install Yarn
RUN npm install -g --force yarn

# Install deps
RUN yarn

# Build
RUN yarn build

# RUN npm run build
EXPOSE 80

# Start
CMD yarn start