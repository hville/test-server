# puppet-call

*puppeteer helpers for testing*

## API

* `server(serverOptions, serverAction): Promise`
  * `serverAction({host, port, root, origin}):Promise`
  * `serverOptions: {root: string, port: number, routes: Object: host: string}`
  * Initiates a server, evaluate `serverAction`, then closes the server before returning the `serverAction` result

## License

[MIT](http://www.opensource.org/licenses/MIT) © [Hugo Villeneuve](https://github.com/hville)
