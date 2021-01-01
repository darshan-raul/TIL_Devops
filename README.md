# TIL_Devops

## AWS

### Ec2
- Nitro vs Xen Hypervisor 
https://www.metricly.com/aws-nitro/

### Lambda

- Lambda Extensions
https://aws.amazon.com/blogs/compute/introducing-aws-lambda-extensions-in-preview/
-https://docs.aws.amazon.com/lambda/latest/dg/runtimes-extensions-api.html

# Monitoring

## ElasticSearch

- Elasticsearch Curator helps you curate, or manage your indices.
https://github.com/elastic/curator
So if you need to rollover the old indexes, a simple command like `curator --host localhost delete indices --older-than 30 --time-unit days --timestring '%Y.%m.%d'`
can help
