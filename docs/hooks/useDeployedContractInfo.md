---
sidebar_position: 5
---

# useDeployedContractInfo

Use this hook to fetch details about a deployed smart contract, including the ABI and address.

```ts
// ContractName: name of the deployed contract
const { data: deployedContractData } = useDeployedContractInfo(contractName);
```

This example retrieves the details of the deployed contract with the specified name and stores the details in the deployedContractData object.
