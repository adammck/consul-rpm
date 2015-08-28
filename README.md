# Consul RPM builder

Forked from [tomhillable/consul-rpm](https://github.com/tomhillable/consul-rpm)
for my own personal use.

## Usage

Set up the environment:

```
export AWS_ACCESS_KEY_ID=xxxx
export AWS_SECRET_ACCESS_KEY=yyyy
export AWS_REGION=us-east-1
export S3_PREFIX=s3://adammck/rpm/consul
```

Run the build (in a Vagrant box), and push RPMs to S3:

```sh
bin/build
bin/publish
```
