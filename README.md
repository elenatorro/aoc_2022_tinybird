## Advent of Code 2022

Advent of Code solved in Tinybird using ClickHouse

* [Tinybird](https://www.tinybird.co)
* [Advent of Code](https://adventofcode.com/2022)

![Tinybird Workspace Screenshot](/images/workspace_screenshot.png)

### Installation

1. Install `tinybird-cli`

```sh
$ virtualenv -p python3.8 .e
$  . .e/bin/activate
$ pip install tinybird-cli
```

2. Log in to a Tinybird workspace

You can watch [how to create a workspace in Tinybird](https://www.youtube.com/watch?v=-jozbkGu31A&ab_channel=Tinybird) or [read the docs](https://www.tinybird.co/docs/cli.html)

```sh
$ tb auth --token <YOUR_TOKEN>
```

3. Push workspace

```sh
$ tb push --fixtures
```
