**Title:** \
**Name:** Robert Mathisen\
**Date:** 3/11/2021 \
\
**Summary:** \
<br/>
**Reason & Reflection:** \
<br/>

**Process:** <br/>
\
**1) Create the VPC.** <br/>
VPC → Virtual Private Cloud → Your VPCs → Create VPC \
IPv4 CIDR block: 10.0.0.0/16 \
Tenancy: Default

**2) Create the Public & Private Subnets.** <br/>
VPC → Virtual Private Cloud → Subnets → Create Subnet\
VPC ID: select the VPC created in Step 1 \
Subnet Name: **Public**Subnet \
Availability Zone: us-east-1**a** \
IPv4 CIDR block: 10.0.**1**.0/24

VPC ID: select the VPC created in Step 1 \
Subnet Name: **Private**Subnet \
Availability Zone: us-east-1**b** \
IPv4 CIDR block: 10.0.**2**.0/24

**3) Create the Internet Gateway.** <br/>
VPC → Virtual Private Cloud → Internet Gateways → Create Internet Gateway\
Name tag: MyIGW 

Select MyIGW → Actions → Attach to VPC \
Available VPCs: select the VPC created in Step 1

**4) Create Route Tables.** <br/>












