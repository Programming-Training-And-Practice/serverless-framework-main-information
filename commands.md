# Serverless Framework Commands.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Help](#help)





## About.





## Documentation.





## General.

| Key/Command                                                                                                                       | Description                                                                                             |
| --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| npm install -g serverless                                                                                                         |                                                                                                         |
| npx serverless config credentials --provider aws --key [keyValue] --secret [secretValue] --profile [IAMUser]                      | Configure authorization.                                                                                |
| npx sls create --template aws-python --path hello-world-python                                                                    | Create lambda.                                                                                          |
| npx sls deploy -v                                                                                                                 | Update all lambda.                                                                                      |
| npx sls deploy function -f [nameFunction]                                                                                         | Update lambda function.                                                                                 |
| npx sls invoke -f [nameFunction] -l                                                                                               | Invoke lambda.                                                                                          |
| npx sls logs -f [nameFunction] -t                                                                                                 | View logs.                                                                                              |
|                                                                                                                                   |                                                                                                         |





## Help.
