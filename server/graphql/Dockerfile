FROM f8app_base:latest

ADD . .
RUN ["npm", "install"]
RUN ["npm", "run", "build"]

ENTRYPOINT [ "node", "lib/index.js" ]
