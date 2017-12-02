aws cloudformation create-stack \
  --region us-east-1 \
  --stack-name "GitHubTrial" \
  --template-url https://github-enterprise.s3.amazonaws.com/cloudformation/trial-1510863838.template \
  --parameters ParameterKey=Instance,ParameterValue=r3.large \
               ParameterKey=Data,ParameterValue=50
