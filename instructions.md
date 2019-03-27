# Instructions

To generate a new aws sam project run:

```bash
docker-compose run sam-init
```

The file `.env` must define the Access keys and the engine:

Example:

```properties
AWS_ACCESS_KEY_ID=[your-access-key-id]
AWS_SECRET_ACCESS_KEY=[your-secret-access-key]
AWS_DEFAULT_REGION=[your-default-region]
LAMBDA_RUNTIME=[aws-lambda-runtime]
LAMBDA_NAME=[lambda-name]
```