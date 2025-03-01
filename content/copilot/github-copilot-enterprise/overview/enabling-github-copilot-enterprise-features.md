---
title: Enabling GitHub Copilot Enterprise features
shortTitle: Enabling Copilot Enterprise
intro: 'Learn how to enable or disable the features available with {% data variables.product.prodname_copilot_enterprise %}.'
versions:
  ghec: '*'
redirect_from:
  - /copilot/github-copilot-enterprise/overview/enabling-github-copilot-enterprise
topics:
  - Copilot
---

## Introduction

To enable users to use {% data variables.product.prodname_copilot_enterprise_short %} features, your {% data variables.product.prodname_ghe_cloud %} enterprise must have a subscription to {% data variables.product.prodname_copilot_enterprise_short %}. For more information, see "[AUTOTITLE](/enterprise-cloud@latest/copilot/quickstart#signing-up-for-github-copilot-enterprise-for-your-enterprise-account)."

Access to {% data variables.product.prodname_copilot_short %} is determined at the enterprise and organization levels:

- Enterprise owners can allow some or all of the organizations in the enterprise to access {% data variables.product.prodname_copilot_short %}. For more information, see "[AUTOTITLE](/enterprise-cloud@latest/admin/policies/enforcing-policies-for-your-enterprise/enforcing-policies-for-github-copilot-in-your-enterprise#managing-access-to-github-copilot-in-your-enterprise)."
- Owners of organizations that have been granted access to {% data variables.product.prodname_copilot_short %} can assign {% data variables.product.prodname_copilot_enterprise %} seats to some or all members of their organization. For more information, see "[AUTOTITLE](/enterprise-cloud@latest/copilot/managing-github-copilot-in-your-organization/managing-access-for-copilot-in-your-organization)."

When access to {% data variables.product.prodname_copilot_short %} has been enabled, features such as the ability to use {% data variables.product.prodname_copilot_short %} on {% data variables.product.prodname_dotcom_the_website %}, can be configured. Features are enabled or disabled at the enterprise or organization level:

- Enterprise owners can set {% data variables.product.prodname_copilot_short %} features to be enabled or disabled for all organizations in the enterprise that have access to {% data variables.product.prodname_copilot_short %}. Alternatively, they can allow each organization to set its own policy for each feature.
- If the enterprise owner has permitted it, organization owners can enable or disable {% data variables.product.prodname_copilot_short %} features for their organization.

This article explains how to enable or disable the features of {% data variables.product.prodname_copilot_enterprise %} at the enterprise level, and for an individual organization.

## About {% data variables.product.prodname_copilot_enterprise_short %} features

{% data variables.product.prodname_copilot_enterprise %} provides AI features to enhance your experience on {% data variables.product.prodname_dotcom_the_website %}, such as the ability to chat with {% data variables.product.prodname_copilot_short %} in the browser and reference context for {% data variables.product.prodname_copilot_short %} from across your project repositories. For more information, see "[AUTOTITLE](/copilot/github-copilot-enterprise/overview/github-copilot-enterprise-feature-set)."

When members are granted access to the features, they'll be notified by email that they have access. The message includes instructions on how to start using the features.

## Enabling or disabling {% data variables.product.prodname_copilot_enterprise %} features for an enterprise

An enterprise owner can choose whether to enable {% data variables.product.prodname_copilot_enterprise %} features for all organizations, disable for all organizations, or allow each organization to choose its own policy for the features. By default, each organization can choose its own policy.

{% data reusables.copilot.copilot-enterprise-enable %}

## Enabling or disabling {% data variables.product.prodname_copilot_enterprise_short %} features for an organization

If your organization's parent enterprise has selected **No policy**, {% data variables.product.prodname_copilot_enterprise %} will be disabled by default for your organization. An organization owner can choose to enable or disable the additional features provided by {% data variables.product.prodname_copilot_enterprise %} for all of the organization's members who have access to {% data variables.product.prodname_copilot_short %}.

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.copilot.policy-settings %}
1. Next to "{% data variables.product.prodname_copilot_short %} in {% data variables.product.prodname_dotcom_the_website %}", select the dropdown menu (labeled **Disabled** by default), then choose from the following options.

   - **Enabled**: The feature is enabled for all members of the organization.
   - **Disabled**: The feature is disabled for all members of the organization.

1. If you select **Enabled**, the option **Give {% data variables.product.prodname_copilot_short %} access to Bing** is displayed.

   Select **Give {% data variables.product.prodname_copilot_short %} access to Bing** to allow {% data variables.product.prodname_copilot_chat_short %} to use search results from Bing to answer questions where appropriate.

## Further reading

- "[AUTOTITLE](/copilot/managing-github-copilot-in-your-organization/managing-access-for-copilot-business-in-your-organization)"
