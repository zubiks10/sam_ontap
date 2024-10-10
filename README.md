# sam_ontap
Deploying SAM_CloudFormation &amp; SAM project

Serverless Framework 4.2.3 now supports AWS SAM and CloudFormation templates, simplifying AWS Lambda development. Deploy SAM/CF projects seamlessly, use Serverless Variables, and streamline your workflow. Perfect for organizations seeking to consolidate serverless tools and standardize development processes.

Get started with SAM and Cloudformation in Serverless Framework by reading the docs.

With this initial release, Serverless Framework enables you to deploy new or existing SAM or CloudFormation projects, without requiring modifications to your existing configuration files. Simply take your raw SAM or CF file in YAML or JSON, and the Serverless Framework will handle the deployment seamlessly.

Serverless Framework will auto-detect SAM/Cloudformation projects in template.yml. You can also provide a custom template file name. We've enabled initial support for samconfig.toml configuration properties that are specific to deployment.