Infrastructure as Code Project Solution
[DUONG NGUYEN MINH]

This project included:

Infrastructure Diagram: Contain infrastructure diagram
CloudFormation Script: Contain script
Screenshort result of stacks
Creation and deletion instructions:

To create network, s3 and udagram server app please run: On Windows: bash create.sh network.yml network-parameters.json bash create.sh s3-bucket.yml s3-bucket-parameters.json aws s3api put-object --bucket myudagrambucket0810 --key index.html --body index.html (upload index.html file to s3) bash create.sh udagram.yml udagram-parameters.json

To delete network, s3 and udagram server app please run: On Windows: bash delete.sh bash delete.sh

The website hosted on the servers link: http://dhq-ud-webap-mgl5cj9krsj9-1848062533.us-east-1.elb.amazonaws.com/