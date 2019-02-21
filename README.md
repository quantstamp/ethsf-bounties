# Submission instructions

Please send all materials to `@mderka` on Telegram.

# Quantstamp Prize for ETH San Francisco Bounty

## Project description

Improve the usability of the Quantstamp protocol for smart contract analysis. The project is broken into three sub-projects. A team can choose to work on any (one or more) of these.

### Improving presentation of the audit reports ($2000)
The Quantstamp protocol reports are JSON files that contain information about the analyzed contract and outputs of security analyzers such as Mythril and Oyente (other analyzers will be added in the future). The raw JSON reports are hard to interpret by non-technical audience. Furthermore, the reports can contain duplicate vulnerabilities as they are detected by multiple analyzers. A successful developer of this bounty would improve the presentation of the Quantstamp protocol reports and/or make progress towards removing the vulnerability duplicates.

#### Resources
1. Betanet UI: https://betanet.quantstamp.com/start 
1. Sample Report: https://s3.amazonaws.com/qsp-protocol-reports-dev/d614a6ae-aac6-480e-af3c-eb59dae1f046.json
1. JSON description of the analyzer report: https://s3.amazonaws.com/qsp-protocol-schema/qsp-v1-report.json
1. Sample audit contract (works when submitted to QSP network): https://s3.amazonaws.com/qsp-protocol-test-contracts/abc7d7d2eff-86cb-4167-8a62-4b99a87b7f50.sol
1. Sample output of analyzers on various smart contracts:
https://consensys.net/diligence/evm-analyzer-benchmark-suite/ 

### Enabling decentralized exchange methods ($1000)
The Quantstamp protocol is powered by the QSP token. As the users might not have QSP tokens handy, the protocol could benefit from an interface that allows users to pay with any ERC20 token that will be automatically converted to QSP for the purposes of requesting the audit. The Kyber decentralized exchange provides means for doing so. There may also be other solutions. A successful developer of this bounty would extend the Quantstamp protocol smart contract with such functionality.

#### Resources
1. Kyber network documentation: https://developer.kyber.network/docs/ArchitectureOverview/
https://github.com/KyberNetwork/smart-contracts/blob/master/integration.md
1. QSP protocol smart contract: 
https://etherscan.io/address/0x74814602062af64fd7a83155645ddb265598220e#code
1. Protocol steps instructions: https://s3.amazonaws.com/qsp-protocol-schema/betanet-instructions.pdf 

### Interfaces for QSP protocol ($2000)
Security audits from the Quantstamp protocol can be requested via web UI provided on betanet.quantstamp.com or via direct interaction with the smart contracts. To simplify the usage and encourage the practice of analyzing smart contracts for security vulnerabilities, the Quantstamp protocol could be integrated directly into the development tools such as Github CI, Truffle, Embark, Remix IDE, and others. Developing and improving a web interface for submitting smart contracts to the protocol would be also considered valuable. A successful developer of this bounty will develop plugins that will enable developers to trigger a security audit directly from the dev tool, or develop a better web interface.

#### Resources
1. Protocol instructions: https://s3.amazonaws.com/qsp-protocol-schema/betanet-instructions.pdf
1. Protocol smart contract source code
https://etherscan.io/address/0x74814602062af64fd7a83155645ddb265598220e#code
1. Truffle: https://truffleframework.com/
1. Remix: https://github.com/ethereum/remix-ide
1. Embark: https://embark.status.im/ 

## Requirements
1. A link to the open-source code must be provided, including instructions how to install dependencies, build, and run
1. A short presentation file must describe your project
1. The contract address(es) of your deployed demo must be provided, either on a testnet of your choice (Kovan, Rinkeby or Ropsten) or on Ethereum mainnet; instructions on how to interact with the contract(s) are appreciated

## Judging Criteria
1. Technicality
1. Originality
1. Practicality
1. WOW Factor

©2018 Quantstamp, Inc.  All rights reserved. 
DISCLAIMER:  This content is provided for informational, personal, non-commercial purposes on an as-is, where-is, and as-available basis. By using this content, you agree that your access and/or use, including but not limited to any associated services, products, protocols, platforms, content, and materials, will be at your sole risk. This content may include descriptions or forward-looking statements concerning concepts under continuing development in testing environments, along with features, functionality, schedules, or design architectures under continuing development, but all of the foregoing are subject to continuing update, modification, cancellation, delay, external dependencies, evolving regulatory frameworks, and/or factors beyond our control and you are cautioned not to place undue reliance on this information. This content shall not be used, copied, modified, redistributed or otherwise disseminated except to the extent expressly permitted by Quantstamp.  FOR AVOIDANCE OF DOUBT, THIS CONTENT, INCLUDING ANY ASSOCIATED SERVICES OR MATERIALS, SHALL NOT BE CONSIDERED OR RELIED UPON AS ANY FORM OF FINANCIAL, INVESTMENT, TAX, LEGAL, REGULATORY, OR OTHER ADVICE.
