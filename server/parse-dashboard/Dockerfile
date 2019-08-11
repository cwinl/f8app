FROM f8app_base:latest

RUN ["npm", "install", "-g", "parse-dashboard"]

ADD config.json config.json

ENTRYPOINT [ \
  "parse-dashboard", \
  "--config", "config.json", \
  "--allowInsecureHTTP" \
]
