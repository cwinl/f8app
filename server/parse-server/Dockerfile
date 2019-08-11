FROM f8app_base:latest

RUN ["npm", "install", "-g", "parse-server"]

ADD . .
RUN [ "npm", "install" ]
RUN [ "npm", "run", "build" ]

ENTRYPOINT [ "parse-server", "config.json" ]
