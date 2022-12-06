## Advent of Code 2022

Advent of Code solved in Tinybird using ClickHouse

* [Tinybird](https://www.tinybird.co)
* [Advent of Code](https://adventofcode.com/2022)

![Tinybird Workspace Screenshot](/images/workspace_screenshot.png)


### Snapshots

* [Day 1 - Calorie Counting 🌟🌟](https://ui.tinybird.co/snapshot/4a4ed6574efe4a12897d17b29e0dfb3d)
* [Day 2 - Rock, paper, scissors 🪨📃✂️](https://ui.tinybird.co/snapshot/ea741c6d3a13494fafc8b02b8edeb3b9)
* [Day 3 - Rucksack Reorganization 🎒](https://ui.tinybird.co/snapshot/bcae8726037047dc891842d3c6a44180)
* [Day 4 - Camp Cleanup 🧹✨](https://ui.tinybird.co/snapshot/78a47a85fc8640e7b95af16bd9e5cb33)
* Day 5 - Supply Stacks 🥫 *(skipped for now)*
* [Day 6 - Tuning Trouble 📡](https://ui.tinybird.co/snapshot/7f7e2e151e4b4d43a89257c62070a621)

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
