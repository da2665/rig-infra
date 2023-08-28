# rig-infra
Rig AWS Infrastructure Repo

Rig users are primarily client facing when using their Frontend apps. But to make this work, our backend is running on an EC2 Auto Scaling Group behind an Application Load Balancer, with an Amazon RDS (MySQL) database for data. This is all being deployed using AWS CloudFormation.
