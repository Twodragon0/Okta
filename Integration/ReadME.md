# Okta Integration Process and Prioritization Guide

## Overview

This document outlines the structured process for integrating internal and external services at Coinone with Okta, addressing the need for clear procedures due to the complexity and large number of services involved.

## Integration Overview

- **Objective**: Central management of fragmented accounts and reduction of incident risks through comprehensive audit logs.
- **Global Usage**: Utilized by over 14,000 companies worldwide, Okta supports integration with more than 7,000 SaaS services, enhancing overall convenience and security.
- **Key Services**: Includes [Google Workspaces](https://workspace.google.com/), [AWS](https://aws.amazon.com/), [Slack](https://slack.com), [Office 365](https://www.office.com/), [Atlassian](https://www.atlassian.com/), and more.

## Priority Setting

Prioritization helps identify which services should be integrated first, focusing on those used most frequently by all employees:

- Google Workspace
- Slack
- Pulse VPN
- NAC
- WiFi
- Atlassian
- Jira

## Okta Integration Process

### 1. Preparation and Planning

Service owners must review licenses and integration requirements before initiating integration with Okta. This phase involves coordination with relevant teams to schedule and plan the integration effort.

### 2. Execution

- **Integration by Service Owner**: Manages role, group, user, and permissions configurations during the integration.
- **Collaboration**: Service owners should collaborate closely with the [Okta Admin team](https://help.okta.com/en/prod/Content/Topics/Admin/admins.htm) during the integration process.

### 3. Post-Integration

- **Issue Resolution**: Service owners handle post-integration issues, escalating to the Okta Admin team as necessary.

## Service Disruption Process

- **Initial Assessment**: Service owners first determine if disruptions are related to Okta integration.
- **Collaboration**: For issues suspected to be linked to Okta, collaboration with the Okta Admin team is essential.
- **Vendor Contact**: Persistent unresolved issues may require contacting the solution vendor directly.

## Service Access and Authentication Process

- **Zero Trust Authentication**: Implements a Zero Trust model requiring continuous verification for accessing all services.
- **Enhanced Authentication**: Services needing stronger authentication measures must plan and coordinate enhancements with the Okta Admin.

## Onboarding and Offboarding Process

- **Data Alignment**: Ensures that all service integrations with Okta align with HR employee data to manage user/group information accurately.
- **Issue Handling**: Any onboarding or offboarding issues are managed in collaboration with the Okta Admin.

## ID/PW/OTP Reset Process

- **Responsibility**: Service owners are tasked with resetting IDs, passwords, or OTPs.
- **Collaboration**: Difficulties with resets should be addressed alongside the Okta Admin team.

## Priority List

Integration priorities are categorized into three levels based on necessity:

- **Tier 1 (High)**: Essential for security enhancements and operational necessities.
- **Tier 2 (Medium)**: Needed for control where access should be managed by specific departments or owners.
- **Tier 3 (Low)**: Benefits overall convenience through streamlined application management.

### Prioritization Criteria

- **Feasibility**: Checks the ability to integrate with Okta, including licenses, permissions, roles, groups, and user configurations.
- **Control Necessity**: Assesses the need for restricted access management by service owners.
- **Convenience**: Evaluates the increased convenience from application management consolidation.

## Best Practices

Adhering to established best practices for Okta integration ensures efficient and secure service management. Regular checks on the compatibility of the SAML and Okta integration processes, especially for enterprise-level licenses, are crucial.

For further assistance or more detailed guidance, contact the [Okta support team](https://support.okta.com) or refer to the Okta integration best practices documentation.
