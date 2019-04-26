Step by step dev

```bash
sam init --runtime python3.7 -o role_sync -n role_sync
```

Run it locally:

```bash
sam build
sam local invoke "RoleSyncFunction" -e schedule_evt.json --profile dh-console-root --region eu-west-1
```

### Local Stack
https://localstack.cloud/