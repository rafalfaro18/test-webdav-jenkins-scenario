# test-webdav-jenkins-scenario

### Instructions
1. `docker-compose up`
2. `localhost:8080`
3. Add project with 'execute shell' build step and execute `duck -l dav://alice@webdav/test/ -qy -p secret1234`
4. Build the project
5. Should build succesfully