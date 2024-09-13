# awesome
A repository that lists &amp; tracks contributions from various stakeholders within the OmniFlix ecosystem.



Node Host Contributions PR Format

contributions/{{name}}.json
```JSON
{
  "name": "Validator Name",
  "account_address": "omniflix1...",
  "validator_address": "omniflixvaloper1...",
  "relayer": {
    "address": "omniflix1....",
    "networks_relaying_with": [
      {
        "name": "cosmoshub",
        "address": ""
      },
      {
        "name": "osmosis",
        "address": ""
      }
    ]
  },
  "explorer": {
    "github_repo_url": "Explorer Github Repo URL",
    "url": "https://explorer.com"
  },
  "archive_node": {
    "rpc": "https://archive-node-rpc.com",
    "rest": "https://archive-node-rest.com"
  },
  "public_endpoints": {
    "rpc": "https://rpc-validator.com",
    "rest": "https://rest-validator.com",
    "grpc": "https://grpc-validator.com"
  },
  "testnet": {
    "validator_address": "testnet validator address",
    "rpc": "",
    "rest": "",
    "grpc": ""
  },
  "dApps": [
    {
      "name": "dApp 1",
      "github_repo_url": "https://github.com/dapp1",
      "url": "https://dapp1.com"
    },
    {
      "name": "dApp 2",
      "github_repo_url": "https://github.com/dapp2",
      "url": "https://dapp2.com"
    }
  ],
  "other_services": [
    {
      "name": "",
      "url": ""
    }
  ],
  "social_accounts": {
      "x": "",
      "telegram": "",
      "discord": ""
  }
}
```
