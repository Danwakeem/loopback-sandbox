# loopback-sandbox

A repository for reproducing [LoopBack community issues][wiki-issues].

[wiki-issues]: https://github.com/strongloop/loopback/wiki/Reporting-issues

## Testing

1. Run `source setup.sh` to initilize the project
2. Install node dependancies `npm i`
3. Run the server `npm start`
4. Send `{"keyword":"abc"}` to the `/MyModel/load` endpoint
5. See Regex error in console