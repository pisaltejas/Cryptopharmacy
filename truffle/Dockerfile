FROM node:14
# Install Truffle
RUN npm install -g truffle@5.5.11
RUN npm config set bin-links false

# Move Contract Files
COPY contracts ./truffle/contracts
COPY migrations ./truffle/migrations
COPY truffle-config.js ./truffle/truffle-config.js
WORKDIR /truffle
