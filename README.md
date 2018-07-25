# Smart Brain Serverless Notes
Serverless Amazon Lambda code related to Udemy course

## AWS Serverless
```bash
# Install Serverless to manage AWS Lambda functions
yarn global add serverless

# Create the serverless Node.js template
sls create -t aws-nodejs

# Add credentials to the cloud service - will be saved in ~/.aws/ folder
sls config credentials --provider aws -key [ACCESS_KEY_ID] -secret [SECRET_ACCESS_KEY]

# Deploy
sls deploy

# Invoke a remote function
sls invoke --function rank

# Attempt to simulate running the function locally
sls invoke local --function rank
```
