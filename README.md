# Learn AWS Boto3

```
import boto3

s3 = boto3.client('s3',
                region_name='us-east-1',
                aws_access_key_id=AWS_KEY_ID,
                aws_secret_access_key=AWS_SECRET)

response = s3.list_buckets()
```


