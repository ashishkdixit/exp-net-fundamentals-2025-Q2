## How to Deploy


### Check YOur AWS Account

```sh
aws sts get-caller-identity
```

### Run the Deployment Script

```sh
cd projects/env_automation
chmod u+x ./bin/deploy
./bin/deploy
```
> We only have to `chmod` the file once to make it executable.