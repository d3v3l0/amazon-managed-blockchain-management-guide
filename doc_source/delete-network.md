# Delete an Amazon Managed Blockchain Network<a name="delete-network"></a>

A blockchain network on Amazon Managed Blockchain remains active as long as there are members\. A network is deleted only when the last member deletes itself from the network\. No member or AWS account, even the creator's AWS account, can delete the network until they are the last member and delete themselves\. When you delete the last member, all resources for that member and the blockchain network are deleted\. For more information, see [Delete a Member in Your AWS Account](managed-blockchain-members.md#managed-blockchain-delete-account-member)\.