An example of Single Page App with CloudFront and S3
====

In this tutorial, we will build a simple SPA with CloudFront and S3. [Single Page App](https://en.wikipedia.org/wiki/Single-page_application) can be a good option when you only need to publish some single blogs and do not need relational database (AWS RDS and Aurora) or DynamoDB.

# Introduction

## App structure

```
root ------- serverless.cf.yaml     # AWS Cloudformation template (in YAML)
     ------- www/                   # the SPA content
                  ----- index.html  # root object of SPA    
```

Services you will need access:

* S3
* Cloudfront

# Deployment

* Step 1: Using CloudFormation to deploy the template. 
* Step 2: Upload the content in `www` to S3.
* In the AWS Cloudfront console, you will find the Cloudfront domain name to access your deployed website.

# Contact

If you have any questions, feel free to reach me at [tuan.nguyenanh.brse@gmail.com](mailto:tuan.nguyenanh.brse@gmail.com).