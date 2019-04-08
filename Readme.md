# 🚤 json-server-multiples-files

Using json-server to server multiples json files in less than *45 seconds* (trust me).

## Getting Started
1. Place your .json files into the `db` folder
2. Install dependencies with `npm install`
3. Run the server : `npm run start:server`

## Output
````
[nodemon] 1.18.10
[nodemon] to restart at any time, enter `rs`
[nodemon] watching: test/mock
[nodemon] starting `node json-server.index.js`


🗒    JSON file loaded : places.json
🗒    JSON file loaded : teams.json

⛴    JSON Server is running at http://localhost:3002
🥁    Endpoint : http://localhost:3002/organisations
🥁    Endpoint : http://localhost:3002/tenders
````

## Built With
- [typicode/json-server](https://github.com/typicode/json-server)

## License
MIT
