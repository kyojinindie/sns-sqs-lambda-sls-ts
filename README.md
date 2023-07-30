# SNS subscription protocol SQS whit a lambda consumer

## Requirements
- aws account
- aws cli
- git
- serverless framework
- typescript

## Deployment

clone repository

```shell
$ git clone https://github.com/kyojinindie/sns-sqs-lambda-sls-ts.git
$ cd sns-sqs-lambda-sls-ts
```

Install dependencies:

```shell
$ npm i
```

Deploy to aws

```shell
$ sls deploy --stage dev
```

## Remove

Remove form aws

```shell
$ sls remove --stage dev
```