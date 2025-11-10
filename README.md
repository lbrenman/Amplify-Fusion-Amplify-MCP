# Amplify Fusion Amplify MCP

An MCP Server implemented in Amplify Fusion for interacting with Amplify.

[Demo video](youtu.be/S9oTX9gWYmw)

Current tools:

* GetAmplifyMarketplacePendingSubscriptions - Get Amplify marketplace pending subscriptions
* UpdateAmplifyMarketplacePendingSubscriptions - Updated Amplify marketplace pending subscriptions Inputs are:
  * approvalState - "approved" or "rejected"
  * subscriptionName - subscription name returned by the `GetAmplifyMarketplacePendingSubscriptions` tool
  * reason - free form text with the reason for approving or rejecting