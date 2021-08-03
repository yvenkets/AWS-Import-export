# AWS-Import-export

To Export


**aws ec2 create-instance-export-task --instance-id instance-id --target-environment vmware --export-to-s3-task file://C:\file.json**



To Import

**aws ec2 import-image --description "My server VM" --disk-containers "file://C:\import\containers.json"**


file.json is for export
container.json is for import.
