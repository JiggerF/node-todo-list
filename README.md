### Description
- A sample api built in node running on Express server and Mongodb
- App is running in docker container

### Localhost api
`http://localhost:3000/task`

### Post to api
```
  curl -vX POST http://localhost:3000/tasks -d @test/test.json --header "Content-Type: application/json"
```
