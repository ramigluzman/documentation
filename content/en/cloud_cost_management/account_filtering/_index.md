---
title: Account Filtering
description: Control what accounts you want to ingest into Cloud Cost Management.
further_reading:
- link: "/cloud_cost_management/"
  tag: "Documentation"
  text: "Learn about Cloud Cost Management"
- link: "/cloud_cost_management/custom"
  tag: "Documentation"
  text: "Learn about Custom Costs"
- link: "/cloud_cost_management/datadog_costs"
  tag: "Documentation"
  text: "Learn about Datadog Costs"
- link: "/cloud_cost_management/saas_costs"
  tag: "Documentation"
  text: "Learn about SaaS Cost Integrations"
- link: "/cloud_cost_management/tag_pipelines"
  tag: "Documentation"
  text: "Learn about Tag Pipelines"
---

## Overview

[Cloud Cost Management][1] enables you to ingest cloud cost data for your AWS accounts, including management accounts for your [AWS Organizations][7].

Use Account Filtering to get granular control of what AWS member accounts you want to pull into [Cloud Cost Management][1]. You will not incur any additional costs for accounts that you filter out.

Currently, Account Filtering is only available for [AWS][8] member accounts, but soon will be available for [Azure][10] subscriptions and [Google Cloud][11] projects.

## Filter accounts

Before attempting to use Account Filtering, ensure you have an AWS management account configured in [Cloud Cost Management][1]. See the [AWS documentation][8] for more information.

Navigate to [**Cloud Costs** > **Accounts**][2] and click on **Manage Account** for the management account you want to filter.

{{< img src="cloud_cost/account_filtering/manage_account.png" alt="Manage Account button on account card" style="width:100%;" >}}

Click on **Billing dataset** to access the Account Filtering UI. Now, you can select / deselect accounts from the table to filter member accounts. You can optionally check the **Include new member accounts by default** box if you want to automatically include new member accounts that get created.

{{< img src="cloud_cost/account_filtering/account_filtering.png" alt="Account Filtering UI to filter AWS member accounts" style="width:100%;" >}}


## Further reading

{{< partial name="whats-next/whats-next.html" >}}

[1]: /cloud_cost_management/
[2]: https://app.datadoghq.com/cost/tags
[3]: /cloud_cost_management/tag_pipelines
[4]: /cloud_cost_management/custom
[5]: /cloud_cost_management/datadog_costs
[6]: /cloud_cost_management/saas_costs
[7]: https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/consolidated-billing.html
[8]: /cloud_cost_management/aws
[9]: https://app.datadoghq.com/cost/settings/accounts
[10]: /cloud_cost_management/azure
[11]: /cloud_cost_management/google_cloud

