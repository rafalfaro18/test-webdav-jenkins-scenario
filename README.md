# test-webdav-jenkins-scenario

### Instructions
1 - `docker-compose up`
2 - `localhost:8080`
3 - Add project with the following build step:
  3.1 - Execute shell `duck -l dav://alice@webdav/test/ -y -p secret1234`
4 - Build the project
5 - Should build succesfully