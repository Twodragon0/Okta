# Okta Integration Process and Prioritization Guide

## Overview

This document outlines the structured process for integrating internal and external services at Coinone with Okta. Given the complexity and number of services (over 69), establishing a clear process and prioritization for Okta integration is essential for visibility and controlled access.

## Integration Overview

- **Objective**: Central management of fragmented accounts and incident risk reduction through audit logs.
- **Global Usage**: Used by over 14,000 companies, Okta integrates with more than 7,000 SaaS services, enhancing convenience.
- **Key Services**: Includes Google Workspaces, AWS, Slack, Office365, Atlassian, etc.

## Priority Setting

Prioritization is necessary to determine which services need to be integrated first. Prioritization is based on usage across all employees and includes testing the following:
- Google Workspace
- Slack
- Pulse VPN
- NAC
- WiFi
- Atlassian
- Jira

## Okta Integration Process

### 1. Preparation and Planning

Each service owner must check licenses and integration specifics before proceeding with Okta. Planning involves scheduling and coordinating with the relevant teams.

### 2. Execution

- **Integration by Service Owner**: Service owners will manage the role, group, user, and permissions configurations during Okta integration.
- **Collaboration**: Integration should be done in collaboration with the Okta Admin.

### 3. Post-Integration

- **Issue Resolution**: Post-integration issues are addressed by the service owner with possible escalation to the Okta Admin.

## Service Disruption Process

- **Initial Assessment**: Service owners assess disruptions to determine if they are related to Okta integration.
- **Collaboration**: If an issue is suspected to be linked to Okta, the service owner collaborates with the Okta Admin.
- **Vendor Contact**: Unresolved issues lead to contacting the solution vendor for resolution.

## Service Access and Authentication Process

- **Zero Trust Authentication**: All services must establish a Zero Trust-based continuous verification for access and authentication.
- **Enhanced Authentication**: For services requiring strengthened authentication, planning and coordination with the Okta Admin are necessary.

## Onboarding and Offboarding Process

- **Data Alignment**: All services integrated with Okta must align with HR employee data for creating or deleting user/group information.
- **Issue Handling**: Any issues during this process are addressed in collaboration with the Okta Admin.

## ID/PW/OTP Reset Process

- **Responsibility**: Service owners are responsible for resetting IDs, passwords, or OTPs.
- **Collaboration**: Difficulties in resolution should be addressed with the Okta Admin.

## Priority List

Services are categorized into three priority levels based on necessity:

- **Tier 1 (High)**: Integration needed due to potential security enhancements and operational necessity.
- **Tier 2 (Medium)**: Control necessity where only specific departments or owners should manage access.
- **Tier 3 (Low)**: Overall convenience through application management consolidation.

### Prioritization Criteria

- **Feasibility**: Ability to integrate with Okta (check licenses, permissions, roles, groups, users).
- **Control Necessity**: Need for restricted access management by service owners.
- **Convenience**: Increased convenience from application consolidation.

## Best Practices

Following established best practices for Okta integration ensures efficient and secure service management. Service owners need to regularly check the SAML and Okta integration process compatibility, especially for enterprise-level licenses.

For further assistance, contact the HR team or refer to detailed documentation in the Okta integration best practices guide.
