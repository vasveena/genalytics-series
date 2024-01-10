This Github repo contains the artifacts for Genalytics Series

1. Run CloudFormation template mda-llm-cfn.yml
2. Once it's complete, run the notebook mda_text-to-sql_with_llm_langchain_bedrock.ipynb

Please note CFN only provisions S3 resource (COVID-19 dataset). You can try out the solution with your own Amazon RDS and Redshift datasets. 
You can also use Sagemaker LLMs from Jumpstart instead of Bedrock. 
