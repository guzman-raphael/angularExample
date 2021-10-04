# FROM vathes/angulardev:angcli7.1.4-angbuild0.11.4
FROM node:16.10-bullseye
# RUN \
#     apt-get --allow-releaseinfo-change update && \
#     apt-get install git -y && \
#     git config --global user.email "angular@email.com" && \
#     git config --global user.name "Angular User"
WORKDIR /main/angularExample
COPY ./frontend/angularExample/package.json ./
RUN npm install
CMD ["npm", "start"]
