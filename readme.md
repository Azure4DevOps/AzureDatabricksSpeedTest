[![Node CI](https://github.com/Azure4DevOps/AzureDatabricksSpeedTest/actions/workflows/nodejs.yml/badge.svg)](https://github.com/Azure4DevOps/GithubAzureDevOpsSpeedTest/actions/workflows/nodejs.yml)
[![Deploy static content to Pages](https://github.com/Azure4DevOps/AzureDatabricksSpeedTest/actions/workflows/static.yml/badge.svg)](https://github.com/Azure4DevOps/GithubAzureDevOpsSpeedTest/actions/workflows/static.yml)

# Azure Databricks Speed Test

Measures the network latency between your browser and Azure Databrick regions.

https://azure4devops.com/AzureDatabricksSpeedTest/

## Building the UI

You can use these commands to build the User Interface:

## Inspired

Forked and inspired from https://github.com/richorama/AzureSpeedTest2
needed to change to fetch instead of Ajax call because of no option to configure CORS

## Thoughts

- Azure Databricks regions response time, at least for me are very similar to https://richorama.github.io/AzureSpeedTest2/ hitting the same Azure region plus few extra 30-50 ms

```
$ npm install
$ npm run build
```

## Regions

1. Run `npm run build`
1. Run the site locally (I use [http-server](https://www.npmjs.com/package/http-server)) to test that the site works.

## Preview
![image](https://github.com/user-attachments/assets/29b7e37a-799f-4fc4-a3da-4fd93c9a6f85)



