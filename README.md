# al-cloudformation-templates

This group of CloudFormation templates have been designed to allow Alert Logic users to quickly provision required resources within AWS with support for the recommended security best-practices. For example, it sets up only the required IAM policy permissions and security group rules so that data can be securely transferred to and from Alert Logic, along with allowing product updates to occur.

## Repository tree

```
├── cloud_defender
│   ├── cloudDefender-cross-account-iam-role(centralized_cloudtrail_account).yaml
│   └── cloudDefender-cross-account-iam-role(protected_account).yaml
├── cloud_insight
│   ├── cloudinsight-cross-account-iam-role(centralized_cloudtrail_account).yaml
│   ├── cloudinsight-cross-account-iam-role(protected_account).yaml
│   └── cloudinsight-essentials-cross-account-iam-role(protected_account).yaml
├── LICENSE
├── log_manager
│   ├── al_lm_cloudtrail-collection-setup.yaml
│   ├── al_lm_s3-collection-setup.yaml
│   ├── clw-to-s3-child-nested.yaml
│   └── clw-to-s3-master.yaml
├── README.md
└── threat_manager
    └── al_tmc_auto-claim.yaml

```
