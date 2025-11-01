# Automation pipeline: AzurePipeline.RDS.StartUp
This repository includes an Azure pipeline designed to automate the process of starting and managing an RDS instance on AWS. It contains commands to launch an RDS instance, monitor its health, and efficiently manage its lifecycle. This configuration helps simplify infrastructure management, reduce manual work, and ensure that instances start and verify reliably within deployment workflows.

### 🛠️For the use the schema
* Aws account and a EC2
* Azure devOps account
* * Create new pipeline
* * Add variables in the pipeline

#### Pipelines variables
```
AWS_ACCOUNT_ACCESS_KEY_ID
AWS_ACCOUNT_SECRET_ACCESS_KEY
AWS_INSTANCE_ID
AWS_REGION
```

### ⚡Triggers in Azure Devops
We can configure pipelines to run on the days we need:
- Create pipeline in Azure Devops
- Setting pipeline with this repository and azure-pipelines.yml
- Select Triggers and Scheduled
- Scheduled detail:

<div align="center">
  <img height="300" width="90%" src="triggers.png"  />
</div>