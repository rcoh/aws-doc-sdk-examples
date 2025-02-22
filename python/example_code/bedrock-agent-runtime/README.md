<!--Generated by WRITEME on 2023-12-13 17:01:16.518867 (UTC)-->
# Amazon Bedrock Agents Runtime code examples for the SDK for Python

## Overview

Shows how to use the AWS SDK for Python (Boto3) to work with Agents for Amazon Bedrock Runtime.

<!--custom.overview.start-->
<!--custom.overview.end-->

*Amazon Bedrock Agents Runtime offers you the ability to run autonomous agents in your application.*

## ⚠ Important

* Running this code might result in charges to your AWS account. For more details, see [AWS Pricing](https://aws.amazon.com/pricing/?aws-products-pricing.sort-by=item.additionalFields.productNameLowercase&aws-products-pricing.sort-order=asc&awsf.Free%20Tier%20Type=*all&awsf.tech-category=*all) and [Free Tier](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all).
* Running the tests might result in charges to your AWS account.
* We recommend that you grant your code least privilege. At most, grant only the minimum permissions required to perform the task. For more information, see [Grant least privilege](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege).
* This code is not tested in every AWS Region. For more information, see [AWS Regional Services](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services).

<!--custom.important.start-->
<!--custom.important.end-->

## Code examples

### Prerequisites

For prerequisites, see the [README](../../README.md#Prerequisites) in the `python` folder.

Install the packages required by these examples by running the following in a virtual environment:

```
python -m pip install -r requirements.txt
```

<!--custom.prerequisites.start-->
> ⚠ You must request access to a model before you can use it. If you try to use the model (with the API or console) before you have requested access to it, you will receive an error message. For more information, see [Model access](https://docs.aws.amazon.com/bedrock/latest/userguide/model-access.html).
<!--custom.prerequisites.end-->

### Single actions

Code excerpts that show you how to call individual service functions.

* [Invoke an agent](bedrock_agent_runtime_wrapper.py#L33) (`InvokeAgent`)

### Scenarios

Code examples that show you how to accomplish a specific task by calling multiple
functions within the same service.

* [Create and invoke agents](../bedrock-agent/scenario_get_started_with_agents.py)

## Run the examples

### Instructions



<!--custom.instructions.start-->
<!--custom.instructions.end-->



#### Create and invoke agents

This example shows you how to do the following:

* Create an execution role for the agent.
* Create the agent and deploy a DRAFT version.
* Create a Lambda function that implements the agent's capabilities.
* Create an action group that connects the agent to the Lambda function.
* Deploy the fully configured agent.
* Invoke the agent with user-provided prompts.
* Delete all created resources.

<!--custom.scenario_prereqs.bedrock-agent-runtime_GettingStartedWithBedrockAgents.start-->
<!--custom.scenario_prereqs.bedrock-agent-runtime_GettingStartedWithBedrockAgents.end-->

Start the example by running the following at a command prompt:

```
python ../bedrock-agent/scenario_get_started_with_agents.py
```


<!--custom.scenarios.bedrock-agent-runtime_GettingStartedWithBedrockAgents.start-->
<!--custom.scenarios.bedrock-agent-runtime_GettingStartedWithBedrockAgents.end-->

### Tests

⚠ Running tests might result in charges to your AWS account.


To find instructions for running these tests, see the [README](../../README.md#Tests)
in the `python` folder.



<!--custom.tests.start-->
<!--custom.tests.end-->

## Additional resources

* [Amazon Bedrock Agents Runtime User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html)
* [Amazon Bedrock Agents Runtime API Reference](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_Operations_Agents_for_Amazon_Bedrock_Runtime.html)
* [SDK for Python Amazon Bedrock Agents Runtime reference](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/bedrock-agent-runtime.html)

<!--custom.resources.start-->
<!--custom.resources.end-->

---

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.

SPDX-License-Identifier: Apache-2.0