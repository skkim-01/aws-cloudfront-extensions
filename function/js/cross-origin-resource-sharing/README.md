# Cross Origin Resource Sharing 


## Description
Support CORS(Cross Origin Resource Sharing) by CloudFront Function 
CloudFront event type for this function: viewer response

## Use Cases
The user is able to add below three headers to enable CORS in viewer response

- Access-Control-Allow-Origin
- Access-Control-Allow-Headers
- Access-Control-Allow-Methods

## Deployment

To deploy the stack, use the AWS CLI

```bash
aws cloudformation deploy --template-file template.yaml --stack-name cross-origin-resource-sharing 
```


## Cleanup

To delete the sample application that you created, use the AWS CLI. Assuming you used your project name for the stack name, you can run the following:

```bash
aws cloudformation delete-stack --stack-name cross-origin-resource-sharing
```