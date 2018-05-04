# Chef Automate Compliance Workshop

The Chef Automate and Compliance Workshop is a 2 day onsite engagement that helps teams that are completely new to Chef or with prior experience, to achieve the following :

1. Learn how to achieve business outcomes with automation using capabilities of the Chef, InSpec and the Chef Automate Platform

2. Understand the value of Continuous Automation in order to increase the speed at which they deliver software changes, reduce risk of deploying infrastructure and applications not meeting compliance requirements, and increase the efficiency by reducing the rate of failed changes

3. Prepare for “life after the workshop” by giving them  the tools and knowledge they need to be successful with Chef Automate and InSpec.

In short, the Chef Automate and Compliance Workshop proves to companies that they can be successful with Chef and that they can achieve business outcomes with the capabilities of Chef Automate and InSpec. 

## Agenda for the Workshop

This Chef Automate and Compliance Workshop is technical, hands-on, and interactive. We need 100% on-site attendance and 100% participation from everyone. We do a lot in a short amount of time, and the participants' complete commitment is the only way to ensure success. Involvement in the workshop is limited to 6-8 people who are subject matter and technical experts in the core team. We also encourage members of the leadership team from your organisation to participate as well. 

The workshop topics familiarize teams with the core concepts of infrastructure automation with Chef, compliance automation with Inspec, and how to have larger success with automation utilising the capabilities of Chef Automate. 

## Infrastructure for the Workshop

All of the infrastructure for the POC will be provided by Chef in a cloud environment. Infrastructure provided includes:
- Chef Automate
- Chef Server
- Infrastructure Nodes
- Chef Workstations (Workstations are Windows Server 2016 VMs with the ChefDK, Visual Studio Code, Atom text editor, and more.)

## Training Location Requirements

The following is required at the training venue:
1. Access to the public internet on port 3389 (RDP).
2. Attendees laptops will need a Remote Desktop Protocol Client. If running a Mac, you can get one for free from the AppStore.
3. Rolling whiteboard preferred, but at least one whiteboard
4. Area on wall/whiteboard for sticky notes for a parking lot.
5. Projector or large screen TV for use by Chef SA to present on.
6. Training room should be reserved for entire length of POC
7. Food - A team that eats together, keeps together !

## Agenda for the Two Days

### Day 1 - Chef Essentials
Duration - Approx 6 - 7 hrs

#### Summary
Learn the basics of Chef by taking a condensed version of Chef Essentials. You’ll learn what it means to turn infrastructure into code so that you can automate the configuration, deployment and management of your Linux and Windows servers. You’ll also learn about Chef architecture and the set of tools included in the Chef Development Kit (ChefDK). Finally, we’ll show you how to test your infrastructure code so that you can deploy with confidence.

1. Introduction
2. Chef Resources
3. Cookbooks
4. Ohai
5. Templates
6. Chef Automate and Chef Server Architecture . (Can spill over to Day 2.)

#### Hands on Labs
The hands on labs simulate the creation of a Linux and Windows webserver.

Windows webserver code - https://github.com/anthonygrees/myiis

CentOS webserver code - https://github.com/anthonygrees/webserver_poc

### Day 2 - Compliance and Chef Automate
Duration - Approx 6 - 7 hrs

#### Summary
This course provides a base level understanding of the capabilities of Chef Automate compliance. This workshop covers how to perform compliance scans against Windows and Linux nodes, and remediate compliance issues with Chef, and run Compliance reports.
In addition, you will learn how to use InSpec to create and modify Chef Automate compliance profiles and learn how to leverage both the built in scanner plus the Audit Cookbook.

1. Chef Automate compliance Intro and Overview
2. Chef Automate compliance User Interfaces
3. Running Scans, Remediation, and Testing on Linux Nodes
4. Running Scans, Remediation, and Testing on Windows Nodes
5. Creating Custom Profiles
6. Using the Audit Cookbook
7. Scheduling Scans and Running Reports

#### Hands on Labs
The hands on labs are for Windows, RHEL and CentOS

https://github.com/anthonygrees/compliance-workshop




## License and Author

* Author:: Anthony Rees <anthony@chef.io>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
