# ACS-project-config
AWS Cloud Solution For 2 Company Websites Using A Reverse Proxy Technology
WARNING: This infrastructure set up is NOT covered by AWS free tier. Therefore, ensure to DELETE  ALL the resources created immediately after finishing the project. Monthly cost may be shockingly high if resources are not deleted. Also, it is strongly recommended to set up a budget and configure notifications when your spendings reach a predefined limit. Watch this video to learn how to configure AWS budget.
The sole aim of this project to build the infrastructure in AWS using terraform.
We will build a secure infrastructure inside AWS VPC (Virtual Private Cloud) network for a fictitious company (Choose an interesting name for it) that uses WordPress CMS for its main business website, and a Tooling Website  for their DevOps team. As part of the company's desire for improved security and performance, a decision has been made to use a reverse proxy technology from NGINX to achieve this.

Cost, Security, and Scalability are the major requirements for this project. Hence, implementing the architecture designed below, ensure that infrastructure for both websites, WordPress and Tooling, is resilient to Web Server's failures, can accomodate to increased traffic and, at the same time, has reasonable cost.
