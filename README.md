# HTTP Prompt Docker

This is a Docker container for [http-prompt](https://github.com/eliangcs/http-prompt). As per [this PR #17](https://github.com/eliangcs/http-prompt/pull/17), the author isn't interested by a container of his tool, but I am.

## Usage

    $ docker run -it --rm sjourdan/http-prompt http://google.com

## Build

    $ make build

## Release

    $ git tag --version <version>
    $ git push --tags
