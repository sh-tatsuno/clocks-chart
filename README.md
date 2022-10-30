# clocks-chart

## Data source

Japanese government's data have been modified for machine-readability. Original data are listed below.

- [birth_jp.csv](https://www.e-stat.go.jp/stat-search/files?page=1&query=%E5%87%BA%E7%94%9F%E7%8E%87&layout=dataset&stat_infid=000032235768)
- [labor_force_jp.csv](https://www.stat.go.jp/data/roudou/longtime/03roudou.html#hyo_2)

## Set up (OSX)

1. [install nodenv](https://github.com/nodenv/nodenv#installation) to allow you to easily switch node version
2. `$ nodenv install` install node version in `.node-version`
3. [install yarn itself](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable) (package manager)
4. `$ yarn install # install modules`

## Check website locally

1. `$ http-server`
2. access [localhost:8080](http://localhost:8080/)
