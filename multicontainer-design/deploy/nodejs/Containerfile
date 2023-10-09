FROM	quay.io/piracarter1/nodejs-12:1
# ARG NEXUS_BASE_URL
MAINTAINER username <username@example.com>

COPY run.sh build ${HOME}/
# RUN npm install --registry=http://$NEXUS_BASE_URL/repository/nodejs/
RUN npm install

EXPOSE	30080

CMD	["./run.sh"]
