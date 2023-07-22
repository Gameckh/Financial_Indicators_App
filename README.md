## Project Documentation

This demo showcases SpreadJS + an online spreadsheet editor, enabling online design and filling of templates, initiating workflow to distribute filling tasks, as well as collecting filled data and executing aggregation tasks.

## Operation steps

[![Watch the video](./pics/000.jpg)](https://videos.grapecity.com.cn/SpreadJS/online/spjs-financial.mp4)

[Official page: Supplementing Financial Indicators](https://www.grapecity.com.cn/developer/spreadjs/industry/financial)

## Start the project

### `environment dependencies`

* Nodejs V12.19.0
* yarn 1.22.10

### `yarn server`

Start mock server to simulate server and database\
The mock server runs by default on [http://localhost:3000](http://localhost:3000), If you encounter port conflicts, you can add the --port parameter to the 'server' command in the package.json under the 'scripts' section. For example:\
`json-server __mock_server/db.json --id key --port 3004`\
Executing `yarn server` will occupy one shell. Please start another shell window to run the demo project.

### `yarn start`

Start the demo project.

Demo runs by default at [http://localhost:9000](http://localhost:9000), If encounter a port conflict, you can modify the value of 'set PORT' in the 'start' command under the 'scripts' section in package.json.

## Template Resources Overview

For the convenience of demonstration, this demo come with several templates for manipulation. Currently, this demo only implements the logic for a balance sheet. Further development can achieve general logic to support more templates.

### 资产负债表.ssjson

Filling Template Example.\
On the create template interface, you can directly import "资产负债表.ssjson" and then complete the field bindings for the "Summary" sheet for the year 2021.

### 资产负债表汇总模板示例.ssjson

Summary Template Example.\
On the create summary template interface, you can directly import "资产负债表汇总模板示例.ssjson". Then, switch to the view template interface to perform the data import and aggregation operation.
