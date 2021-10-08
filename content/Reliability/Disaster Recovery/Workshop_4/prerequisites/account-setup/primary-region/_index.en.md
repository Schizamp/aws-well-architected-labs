+++
title = "Primary Region"
date =  2021-05-11T11:43:28-04:00
weight = 2
+++

### Deploying the Amazon CloudFormation Template

1.1 Deploy the application to the primary region **N. Virginia (us-east-1)** by launching this [CloudFormation Template](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/template?stackName=Active-Primary&templateURL=https://ee-assets-prod-us-east-1.s3.amazonaws.com/modules/630039b9022d4b46bb6cbad2e3899733/v1/HotStandby.yaml).

1.2  Specify the stack parameters.

{{% notice info %}}
**Leave isPrimary and LatestAmiId as the default values**
{{% /notice %}}

1.3 Click **Next** to continue.

{{< img pr-4.png >}}

1.4 Leave the **Configure stack options** page defaults and click **Next** to continue.

1.5 Scroll to the bottom of the page and click the **checkbox** to acknowledge IAM role creation, then click **Create stack**.

{{< img pr-5.png >}}

{{< prev_next_button link_prev_url="../s3-access" link_next_url="../secondary-region/" />}}

