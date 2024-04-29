# Document Strategies
Strategies focused on broadcasting documents.

<br/>

## 100-minFill-fillNotRequired-dashpay-contactInfo
Registers 30 start identities with 0.4 DASH each and 100 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 [minimal contactInfo document](https://github.com/dashpay/platform-strategy-tests/blob/master/documents/examples/minFill-fillNotRequired-dashpay-contactInfo.json) per second to all 100 contracts.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 83% | 12 DASH | 99 | 21.2 | 388 | 3.05 | 59630 | 50074 | 24 | 123 | 9404 | - |
| v1.0.0-dev.10 | 10 min | 75% | 12 DASH | 98 | 14.5 | 388 | 2.24 | 59330 | 44798 | 155 | 250 | 14125 | - |

<br/>

## 100-maxFill-fillNotRequired-dashpay-contactInfo
Registers 30 start identities with 0.5 DASH each and 100 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 [maximal contactInfo document](https://github.com/dashpay/platform-strategy-tests/blob/master/documents/examples/maxFill-fillNotRequired-dashpay-contactInfo.json) per second to all 100 contracts.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 81% | 15 DASH | 87 | 13.4 | 283 | 2.85 | 52830 | 43336 | 31 | 6944 | 2519 | - |

<br/>

## 100-minFill-fillNotRequired-dpns-preorder
Registers 30 start identities with 0.4 DASH each and 100 [dpns preorder contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dpns_contract_preorder.json) variants, then submits 1 [preorder document](https://github.com/dashpay/platform-strategy-tests/blob/master/documents/examples/dpns-preorder.json) per second to all 100 contracts.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 84% | 12 DASH | 98 | 48.6 | 905 | 3.25 | 59330 | 50101 | 3 | 343 | 8875 | - |
| v1.0.0-dev.10 | 10 min | 74% | 12 DASH | 97 | 23.1 | 968 | 1.45 | 58830 | 43731 | 0 | 732 | 14352 | - |

<br/>

## 80-minFill-fillNotRequired-dashpay-contactInfo
Registers 30 start identities with 0.4 DASH each and 80 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 [minimal contactInfo document](https://github.com/dashpay/platform-strategy-tests/blob/master/documents/examples/minFill-fillNotRequired-dashpay-contactInfo.json) per second to all 80 contracts.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 99% | 12 DASH | 79 | 21.2 | 388 | 3.05 | 47710 | 47611 | 16 | 60 | 17 | - |

<br/>

## 80-maxFill-fillNotRequired-dashpay-contactInfo
Registers 30 start identities with 0.5 DASH each and 80 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 [maximal contactInfo document](https://github.com/dashpay/platform-strategy-tests/blob/master/documents/examples/maxFill-fillNotRequired-dashpay-contactInfo.json) per second to all 80 contracts.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 90% | 15 DASH | 71 | 13.4 | 283 | 2.85 | 43150 | 38882 | 19 | 4245 | 0 | - |

<br/>

## 80-minFill-fillNotRequired-dpns-preorder
Registers 30 start identities with 0.3 DASH each and 80 [dpns preorder contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dpns_contract_preorder.json) variants, then submits 1 [preorder document](https://github.com/dashpay/platform-strategy-tests/blob/master/documents/examples/dpns-preorder.json) per second to all 80 contracts.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 99% | 9 DASH | 78 | 39.4 | 895 | 2.64 | 47390 | 47138 | 2 | 317 | 45 | - |

<br/>

## 50-minFill-fillNotRequired-dashpay-contactInfo
Registers 30 start identities with 0.3 DASH each and 50 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 [minimal contactInfo document](https://github.com/dashpay/platform-strategy-tests/blob/master/documents/examples/minFill-fillNotRequired-dashpay-contactInfo.json) per second to all 50 contracts.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 99% | 9 DASH | 49 | 23.7 | 388 | 3.7 | 29930 | 29900 | 0 | 29 | 0 | - |
| v1.0.0-dev.10 | 10 min | 99% | 9 DASH | 49 | 13.2 | 388 | 2.0 | 29730 | 29460 | 0 | 264 | 0 | - |

<br/>

## 50-maxFill-fillNotRequired-dashpay-contactInfo
Registers 30 start identities with 0.4 DASH each and 50 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 [maximal contactInfo document](https://github.com/dashpay/platform-strategy-tests/blob/master/documents/examples/maxFill-fillNotRequired-dashpay-contactInfo.json) per second to all 50 contracts.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 90% | 12 DASH | 45 | 14.4 | 283 | 3.1 | 27630 | 25041 | 2 | 2587 | 0 | - |

<br/>

## 50-minFill-fillNotRequired-dpns-preorder
Registers 30 start identities with 0.2 DASH each and 50 [dpns preorder contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dpns_contract_preorder.json) variants, then submits 1 [preorder document](https://github.com/dashpay/platform-strategy-tests/blob/master/documents/examples/dpns-preorder.json) per second to all 50 contracts.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 99% | 6 DASH | 49 | 33.5 | 529 | 3.7 | 29930 | 29906 | 0 | 24 | 0 | 0 |
| v1.0.0-dev.10 | 10 min | 99% | 6 DASH | 49 | 28.0 | 968 | 1.7 | 29630 | 29178 | 0 | 452 | 0 | - |
