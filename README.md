## A Docker Container for DynamoDB Local

A Docker container for a [DynamoDB Local provided by Amazon](https://aws.amazon.com/blogs/aws/dynamodb-local-for-desktop-development/) for local development.

### Building the image

```
docker build -t dynamodb-container .
```

### Running the image

```
docker run -p 8000:8000 -d dynamodb-container:latest
```

