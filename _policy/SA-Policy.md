---
category: policy
title: SA-policy
tags: SA
---
# {{ site.data.ssp.system }} System and Services Acquisition Policy

## 1. Purpose of Policy
The purpose of this policy is to ensure that {{ site.data.ssp.system }} establishes requirements for a comprehensive program for developing, implementing and maintaining relevant information to support system and services acquisition policy objectives and security posture of the organization.
The {{ site.data.ssp.system }} program includes a library of security policies that address federal and non-federal requirements. These policies guide and govern the actions of {{ site.data.ssp.system }} employees and contractors in conducting any United States (U.S.) business.

This policy is written to include the following:
* Allocation of Resources
* Life Cycle Support
* Acquisitions
* Information System Documentation
* Software Usage Restrictions
* User-installed Software
* Security Engineering Principles
* External Information System Services
* Developer Configuration Management
* Developer Security Testing

## 2. Scope of Policy
This policy applies to all users, systems, networks, components, services and processes in or accessing the {{ site.data.ssp.system }} Production environment, and all services, applications and products in General Availability.  This includes cloud infrastructure components, leveraged services and other elements used to deliver {{ site.data.ssp.system }} products and services.

Please see the {{ site.data.ssp.system }} Governance Policy for further information on Management Commitment, Compliance and Enforcement, Review & Update processes, and Penalties.

## 3. Policy
The access and use of Information Technology (IT) resources shall be in compliance with applicable Federal Information Processing Standards (FIPS) and National Institute of Standards and Technology (NIST) Special Publications, International Organization for Standards (ISO) and {{ site.data.ssp.system }} policies and standards.

#### Allocation of Resources

* {{ site.data.ssp.system }} will implement a mission/business process planning
* {{ site.data.ssp.system }} will conduct annual assessment to ensure controls are implemented correctly, operating, and producing the desire artifacts;
* {{ site.data.ssp.system }} will generate a Security Assessment Report and document the outcome of [annual] assessment; and
* {{ site.data.ssp.system }} will establish a discrete line item for information security in organizational programming and budgeting documentation.

### Life Cycle Support
* {{ site.data.ssp.system }} will manage the information system using a system development life cycle methodology that includes information security considerations;
* {{ site.data.ssp.system }} will define and document information system security roles and responsibilities throughout the system development life cycle; and
* {{ site.data.ssp.system }} will identify individuals having information system security roles and responsibilities.

### Acquisitions
* {{ site.data.ssp.system }} will include the following requirements and/or specifications, explicitly or by reference, in information system acquisition contracts based on an assessment of risk and in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, and standards:
  * Security functional requirements and specifications;
  * Security-related documentation requirements; and
  * Development and evaluation-related assurance requirements.
* {{ site.data.ssp.system }} requires that acquisition documents that vendors/contractors provide information describing the functional properties of the security controls to be employed within the information system, information system components, or information system services in sufficient detail to permit analysis and testing of the controls.
* {{ site.data.ssp.system }} requires that each information system component acquired is explicitly assigned to an information system, and that the owner of the system acknowledges this agreement.

### Information System Documentation
* {{ site.data.ssp.system }} will develop and maintain administrator documentation for the information system, making it available upon request by authorized personnel, that includes the following:
  * Secure configuration, installation, and operation of the information system;
  * Effective use and maintenance of security features/functions; and
  * Known vulnerabilities regarding configuration and use of administrative (i.e. privileged) functions.
* {{ site.data.ssp.system }} will develop and maintain user documentation for the information system, making it available upon request by authorized personnel, that includes the following:
  * User-accessible security features/functions and how to effectively use those security features/functions;
  * Methods for user interactions with the information system; and
  * User responsibilities in maintaining the security of the information and information system.
* {{ site.data.ssp.system }} will document attempts to obtain information system documentation when such documentation is either unavailable or nonexistent.
* {{ site.data.ssp.system }} will maintain vendor documentation, as required and protected, that describes the functional properties of the security controls employed within the information system with sufficient detail to permit analysis and testing.
* {{ site.data.ssp.system }} will maintain vendor documentation, as required and protected, that describes the high-level design of the information system in terms of subsystems and implementation details of the security controls employed within the system with sufficient detail to permit analysis and testing.

### Software Usage Restrictions
* {{ site.data.ssp.system }} will use software and associated documentation in accordance with contract agreement and copyright laws;
* {{ site.data.ssp.system }} will employ a tracking system for software and associated documentation protected by quantity licenses to control copying and distribution; and
* {{ site.data.ssp.system }} will document the utilization of peer-to-peer file sharing technology ensuring that it will not be used for unauthorized distribution, display, performance, or reproduction of copyrighted material.

### User-installed Software
* {{ site.data.ssp.system }} plans will document what software may or may not be installed; security patches installation, and who is authorized to install such software.

### Security Engineering Principles
* {{ site.data.ssp.system }} will apply information system security engineering principles in to the specifications, design, development, implementation, and modification of the information system.

### External Information System Services
* {{ site.data.ssp.system }} will require external information system providers to comply with {{ site.data.ssp.system }} information system requirements and employ appropriate security controls in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance;
* {{ site.data.ssp.system }} will define and document government oversight and user roles and responsibilities with regards to external information system services
* {{ site.data.ssp.system }} will monitor security control compliance by external service providers.

### Developer Configuration Management
* {{ site.data.ssp.system }} requires that information system developers/integrators:
  * Perform configuration management during information system design, development, implementation, and operation;
  * Manage and control changes to the information system;
  * Implement only organization-approved changes;
  * Document approved changes to the information system; and
  * Track security flaws and flaw resolution.

### Developer Security Testing
* {{ site.data.ssp.system }} requires that information system developers/integrators, in consultation with associated security personnel;
  * Create and implement a security test and evaluation plan;
  * Implement a verifiable flaw remediation process to correct weaknesses and deficiencies identified during the security testing and evaluation process; and
  * Document the results of the security testing/evaluation and flaw remediation processes.
