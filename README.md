# al-cloudformation-templates

This group of CloudFormation templates have been designed to allow Alert Logic users to quickly provision required resources within AWS with support for the recommended security best-practices. For example, it sets up only the required IAM policy permissions and security group rules so that data can be securely transferred to and from Alert Logic, along with allowing product updates to occur.

## Repository tree
.
├── cloud_defender
│   ├── cloudDefender_auto-claim_v3(uk).yaml
│   ├── cloudDefender_auto-claim_v3(us).yaml
│   ├── cloudDefender-cross-account-iam-role(centralized_cloudtrail_account).yaml
│   └── cloudDefender-cross-account-iam-role(protected_account).yaml
├── cloud_insight
│   ├── cloudinsight-cross-account-iam-role(centralized_cloudtrail_account).yaml
│   ├── cloudinsight-cross-account-iam-role(protected_account).yaml
│   └── cloudinsight-essentials-cross-account-iam-role(protected_account).yaml
├── log_manager
│   ├── clw-to-s3-child-nested.yaml
│   ├── clw-to-s3-master.yaml
│   ├── logmanager-cloudtrail-collection-setup_v1.1.yaml
│   └── logmanager-s3-collection-setup_v1.1.yaml
├── threat_manager
│   ├── tmc_auto-claim_v3(uk).yaml
│   ├── tmc_auto-claim_v3(us).yaml
│   └── tmc_us-gov_v3.yaml
.

5 directories, 17 files
