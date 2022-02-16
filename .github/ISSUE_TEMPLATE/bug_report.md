Page 489
I'm getting this error when tried to Enable CloudTrail for all AWS region and configure the S3 bucket to send logs
aws cloudtrail create-trail --name AWSCookbook903Trail \
     --s3-bucket-name awscookbook903-$RANDOM_STRING \
     --is-multi-region-tril
 An error occurred (InsufficientS3BucketPolicyException) when calling the CreateTrail operation: Incorrect S3 bucket policy is detected for bucket: awscookbook903  

