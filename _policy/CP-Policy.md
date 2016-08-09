---
category: policy
title: CP-policy
tags: CP
---
# {{ site.data.ssp.system }} Contingency Planning Policy

## 1. Purpose of Policy
Contingency planning is a component of business continuity, disaster recovery and risk management. Its major objectives are to ensure containment of damage or injury to, or loss of, personnel and property, and continuity of the key operations of the organization.

The purpose of this policy is to ensure that {{ site.data.ssp.system }} establishes requirements for a comprehensive program for developing, implementing and maintaining relevant information to support contingency planning objectives and security posture of the organization.

The {{ site.data.ssp.system }} program includes a library of security policies that address federal and non-federal requirements. These policies guide and govern the actions of {{ site.data.ssp.system }} employees and contractors in conducting any United States (U.S.) business.

This policy is written and includes the following:
* Contingency Plan
* Contingency Training
* Contingency Plan Testing
* Alternate Redundant Storage Site
* Alternate Redundant  Processing Site
* Telecommunications Services
* Information system backup
* Information system  recovery and reconstitution

## 2. Scope of Policy
This policy applies to all users, systems, networks, components, services and processes in or accessing the {{ site.data.ssp.system }} Production environment, and all services, applications and products in General Availability.  This includes cloud infrastructure components, leveraged services and other elements used to deliver {{ site.data.ssp.system }} products and services.

Please see the {{ site.data.ssp.system }} Governance Policy for further information on Management Commitment, Compliance and Enforcement, Review & Update processes, and Penalties.

## 3. Policy
The access and use of Information Technology (IT) resources shall be in compliance with applicable Federal Information Processing Standards (FIPS) and National Institute of Standards and Technology (NIST) Special Publications, International Organization for Standards (ISO) and {{ site.data.ssp.system }} policies and standards.

### Contingency Planning
{{ site.data.ssp.system }} will implement contingency plans that:
* Identify essential missions and business functions and associated contingency requirements
* Provide recovery objectives, restoration priorities, and metrics
* Identify roles and responsibilities
* Maintain essential mission and business functions despite information system disruption, compromise, or failure; and
* Identify full system restoration without deterioration of the security measure as originally planned and implemented.

### Contingency Training
* {{ site.data.ssp.system }} will provide designated contingency personnel with annual training on their roles and responsibilities.

### Contingency Plan Testing and Exercises
* On an annual basis, {{ site.data.ssp.system }} will conduct a test of the contingency plan with all appropriate personnel identified as part of the Contingency Plan and report finding back to {{ site.data.ssp.system }} Senior Management
* {{ site.data.ssp.system }} will review and provide appropriate Contingency Plan updates based off annual tests.

### Alternate Redundant Storage Site
* {{ site.data.ssp.system }} will utilize cloud computing infrastructure capabilities to leverage established redundant storage sites within (Amazon Web Services (AWS)  US regions) and federally located facilities for the storage and recovery of information
* All regional sites and availability zones should be physically separated from other sites and {{ site.data.ssp.system }} will identify and remediate potential accessibility problems to the regional sites in the event of an area-wide disruption or disaster.

### Alternate Redundant Processing Site
* {{ site.data.ssp.system }} shall utilize the capabilities of cloud infrastructure as a service (IaaS), to establish redundant processing sites; including necessary agreements to permit the resumption of information operations for essential mission and business functions within an approved time period when the primary processing capabilities are unavailable
* {{ site.data.ssp.system }} will ensure the availability of all provided services, processes, and work flows required to resume operations are available to support the {{ site.data.ssp.system }} defined time period for resumption
* {{ site.data.ssp.system }} will ensure to use regional sites that are physically separated from other storage sites within the united states
* {{ site.data.ssp.system }} will identify and remediate potential accessibility problems to the AWS site in the event of an area-wide disruption or disaster
* {{ site.data.ssp.system }} alternative processing site agreements will contain priority-of-service provisions in accordance with {{ site.data.ssp.system }} availability requirements
* {{ site.data.ssp.system }} will ensure that redundant processing sites provides information security measures equivalent to that of a primary processing site.

### Telecommunications Services
* {{ site.data.ssp.system }} shall leverage cloud computing redundancy capabilities for alternative telecommunication services for the resumption of system operations for essential missions and business functions within an approved time period from when the primary telecommunications capabilities are unavailable
* {{ site.data.ssp.system }} will leverage primary and alternate telecommunications service agreements that contain priority-of-service provisions in accordance with {{ site.data.ssp.system }} availability requirements
* {{ site.data.ssp.system }} request telecommunications service priority for all telecommunications services used for national security emergency preparedness in the event that either the primary or alternate telecommunications services are unavailable
* {{ site.data.ssp.system }} will utilize the cloud infrastructure secondary telecommunication service providers to reduce the likelihood of a single point-of-failure with primary telecommunications service provider.

### Information System Backup
* {{ site.data.ssp.system }} conducts pre-defined backups of user-level information contained in the information system.
* {{ site.data.ssp.system }} conducts pre-defined backups of system-level information contained in the information system.
* {{ site.data.ssp.system }} conducts pre-defined backups of information system documentation including security related documentation.
* {{ site.data.ssp.system }} will protect the confidentiality an integrity of backup information
* {{ site.data.ssp.system }} will test backup of information on an [annual] basis to verify media reliability and information integrity.

### Information System Recovery and Reconstitution
* {{ site.data.ssp.system }} will provide for the recovery and reconstitution of the information system to a known state after a disruption, compromise, or failure.
* {{ site.data.ssp.system }} implements transaction recovery for systems that is transaction-based.
* {{ site.data.ssp.system }} will provide compensating security controls in the event that system recovery and reconstitution of its information systems has not been fully restored.
