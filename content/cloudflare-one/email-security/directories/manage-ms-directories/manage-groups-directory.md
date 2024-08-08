---
title: Manage groups in your directory
pcx_content_type: how-to
weight: 3
---

# Manage groups in your directory

Email Security allows you to view and manage your groups directory and their [impersonation registry](/cloudflare-one/email-security/detection-settings/impersonation-registry/). When a group is added to the registry, all members are registered by default. 

To manage your group directory, on the **MS directory** page, select **Groups**.

## Add groups to registry

Email Security allows you to add group names to the registry. 

To add a single group to the registry:

1. Select the group name you want to add.
2. Select the three dots > **Add to registry**.

To add multiple groups to the registry at once:

1. Select the group names you want to add to the registry.
2. Select the **Action** dropdown list.
3. Select **Add to registry**.

## Remove groups from registry

Email Security allows you to remove group names from the registry. 

To remove a single group from the registry:

1. Select the group name you want to remove.
2. Select the three dots > **Remove from registry**.

To remove multiple groups from the registry at once:

1. Select the group names you want to remove from registry.
2. Select the **Action** dropdown list.
3. Select **Remove from registry**.

## Filter impersonation registry

You can filter the list of group names by registered and unregistered.

A group name is registered when it is part of the [impersonation registry](/cloudflare-one/email-security/detection-settings/impersonation-registry/). A group name is unregistered when they are not part of the impersonation registry.

To filter the list, under the **Impersonation registry** dropdown, select one of the following:
   - **All**: To view registered and unregistered groups.
   - **Registered**: To view registered groups.
   - **Unregistered**: To view unregistered groups.