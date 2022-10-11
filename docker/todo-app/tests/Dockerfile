FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests

ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .
COPY jest.config.js .

ENTRYPOINT [ "npm", "test" ]
