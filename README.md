# &lt;e-charts&gt;

> A bare minimum custom element starter-kit using [X-Tag](http://x-tags.org/).
>
> Looking for a working example? Check [e-charts](https://github.com/junmer/e-charts).

## Demo

[Check it live!](http://junmer.github.io/e-charts)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install e-charts --save
```

Or [download as ZIP](https://github.com/jumer/e-charts/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/e-charts/dist/e-charts.html">
    ```

3. Start using it!

    ```html
    <e-charts></e-charts>
    ```

## Options

[echarts options](http://echarts.baidu.com/doc/doc.html#Option)

## Methods

[echarts Methods](http://echarts.baidu.com/doc/doc.html#实例方法)


## Events

`todo` mixin [echarts Events](http://echarts.baidu.com/doc/doc.html)



## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/junmer/e-charts/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
