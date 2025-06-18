# Deployment

Remember to update the `.env` file before starting application, or else the application will crash.

Script to deploy the application:

```bash
docker-compose -f docker-compose.base.yaml -f docker-compose.(prod/test).yaml up -d --pull=always
```
