﻿# Organization

An organization in Devant is a logical grouping of users and user resources. A first-time user must create an organization and be a member of it when signing in to Devant. Users and resources in an organization cannot access resources in another organization unless an admin of the other organization invites them and adds them as member of that organization. A user cannot create more than one organization.

## Switch organizations

If you are a member of more than one organization, you can switch from one organization to another when necessary. To do this, select the required organization from the **Organization** list in the Devant Console header.

{% include "../administer/inviting-members.md" %}

## Manage user permission

Devant manages user permissions with groups and roles.

### Groups

A group in Devant is a collection of users, each with one or more roles assigned to them. Users within a group inherit the permissions associated with the roles assigned to that group. For instance, if a user is added to the `API Publisher` group, they will automatically receive the `API Publisher` role.

Devant comes with predefined groups already configured with specific roles, as follows:

- **API Publisher**: A collection of users who have the API Publisher role.
- **API Subscriber**: A collection of users who have the API Subscriber role.
- **Admin**: A collection of users who have the Admin role.
- **Billing Admin**: A collection of users who have the Billing Admin role.
- **Devant DevOps**: A collection of users who have the Devant DevOps role.
- **Developer**: Users who develop, deploy, and manage integrations at scale.
- **External API Subscriber**: A collection of users who have the External API Subscriber role.

When creating a new group to invite members, be sure to assign a role to the group to ensure users have the required permissions.

### Roles

Devant roles are defined as follows:

- **API Publisher**: An API publisher can discover, create, publish, delete, test, and manage an API.
- **API Subscriber**: An API subscriber is a developer in a particular organization. An API subscriber can subscribe to an API, manage subscriptions, manage integrations, generate API keys, and manage API keys.
- **Admin**: An administrator is responsible for all administration tasks, including user management, customizing the Developer Portal, managing projects, enabling analytics, managing domains, etc.
- **Billing Admin**: Is responsible for billing administration that includes viewing tiers, creating and viewing organizations, managing invoices, viewing and creating subscriptions, and viewing and creating payment methods.
- **Devant DevOps**: A Devant DevOps user is a user with access to the Devant DevOps portal, enabling them to actively manage, ensure dependable deployment, and monitor integrations.
- **Developer**: Users who develop, deploy, and manage integrations at scale. 
- **External API subscriber**: External API subscribers are API consumers who have access only to the API Developer Portal. They can join an organization with the sole purpose of consuming APIs.
- **Environment Manager (Deprecated)**: Manages deployment environments.

## Organization ID

The Organization ID serves as a unique identifier for each organization. To get the organization ID, follow the steps below:

1. Go to [https://console.devant.dev/](https://console.devant.dev/) and sign in. This opens the project home page.
2. Click on the **Organization** list on the header and select your organization.
3. In the left navigation, expand **Admin** dropdown and click **Settings**.
4. Under **Access Control**, click **Copy ID**.

## Organization Handle

The organization handle is a unique string that directly corresponds to your organization's name. To get the organization handle, follow the steps below:

1. Go to [https://console.devant.dev/](https://console.devant.dev/) and sign in. This opens the project home page.
2. Click on the **Organization** list on the header and select your organization.
3. In the left navigation, expand **Admin** dropdown and click **Settings**.
4. Under **Access Control**, click **Copy Handle**.
