# Agoric Validator Pledge
[kjnodes Explorer Link](https://main.explorer.agoric.net/validator/agoricvaloper1ku5sm2twlsywdrp4wz3kfwgyrtqtp0lpr3nvk8)
To receive and maintain delegation from the Agoric OpCo, I, kjnodes hereby commit to the following work and support for the benefit of the Agoric Network and Community. If, for any reason, I do not meet these commitments then I understand that I may lose delegation staked to me by the Agoric Operations Company and/or any other associated organizations. :

1. The hardware my node will run meets the requirements detailed in the [Agoric Validator Runbooks](https://github.com/Agoric/agoric-sdk/wiki/Runbook%...)

2. My node will have an uptime of at least 95%

3. I will set a reasonable commission rate between 3% to 10%

4. I commit to not exceed 10% voting power

5. I will actively participate in security and upgrade governance proposals found on [Commonwealth.im](https://commonwealth.im/agoric)

6. I will report bugs I discover through the process described in the [Agoric Reporting a Security Bug Runbook](https://github.com/Agoric/agoric-sdk/wiki/Runbook%...)

7. I will follow the guidelines described in the [Agoric Security Coordination - Emergency Bug Response with Chain Validators Runbook](https://github.com/Agoric/agoric-sdk/wiki/Runbook%...) to maintain the health of the chain

8. I will notify impacted parties in case of node outage.

9. I will strive to capture and share observability metrics to help diagnose and troubleshoot network and node performance issues

10. I commit to network contributions listed below:

Category 1: Infrastructure

I will run an RPC endpoint , I will build a block explorer, validator dashboard, or other community tool

List of our contributions for Agoric project:

Infrastructure Mainnet:
- RPC endpoint: https://agoric-mainnet.rpc.kjnodes.com
- API endpoint: https://agoric-mainnet.api.kjnodes.com
- P2P peer: `04dfb6dfa2696a46eec6748d2c6842c82030cb8d@agoric-mainnet.rpc.kjnodes.com:27656`

Plans for the future: Provide with services like State-Sync, Snapshots and IBC relayer

Infrastructure Testnet:
- RPC endpoint: https://agoric-testnet.rpc.kjnodes.com
- API endpoint: https://agoric-testnet.api.kjnodes.com
- P2P peer: `80b8acb4862f3a93072359911e73fedd1be625b8@agoric-testnet.rpc.kjnodes.com:27656`
- Explorer: https://explorer.kjnodes.com/agoric

We are also actively participating in chain governance and running testnet validator node to help test chain upgrades before they reach mainnet.

Category 2: Community Growth

Our guides for Agoric mainnet:
https://github.com/kj89/testnet_manuals/blob/main/agoric

Our guides for Agoric testnet:
Mainnet: https://github.com/kj89/testnet_manuals/blob/main/agoric/emerynet

We have developed our own monitoring and alerting dashboard for Cosmos ecosystem that is widely used by other validators in many projects

As a contribution to Agoric community I would like to share our guide on how to setup monitoring dashboard and alerting for your validator in just few minutes. This tool will notify you in telegram if some of critical metrics change. Also you will get pretty looking dashboard to follow your node and chain health status.
Guide can be found [here](https://github.com/kj89/testnet_manuals/blob/main/agoric/monitoring/README.md)
For video as an example I used Agoric devnet validator. You can watch it [here](https://www.youtube.com/watch?v=b5pTCFVQdOQ)

## Dashboard contents
Grafana dashboard is devided into 4 sections:
- **Validator health** - main stats for validator health. connected peers and missed blocks

![image](https://user-images.githubusercontent.com/50621007/160629676-bc3c4f0f-66df-4a5f-9844-dca308072e7a.png)

- **Chain health** - summary of chain health stats and list of top validators missing blocks

![image](https://user-images.githubusercontent.com/50621007/160629937-52253f35-8782-4dd2-80cc-ad31d0231a84.png)

- **Validator stats** - information about validator such as rank, bounded tokens, comission, delegations and rewards

![image](https://user-images.githubusercontent.com/50621007/160630119-0abad099-b138-4f61-9e73-49506c2295ff.png)

- **Hardware health** - system hardware metrics. cpu, ram, network usage

![image](https://user-images.githubusercontent.com/50621007/160630213-5e92b3ce-92c9-4f48-8856-383ca884b621.png)

