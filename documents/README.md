# Document Strategies
Strategies focused on broadcasting documents.

<br/>

## 100_dashpay_contactInfo_per_second_minFill
Registers 30 start identities with 0.4 DASH each and 100 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 minimal contactInfo document per second to all 100 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 19, 2024 | 10 min | 83% | 12 DASH | 99 | 21.2 | 388 | 3.05 | 59630 | 50074 | 24 | 123 | 9404 | - |
| April 17, 2024 | 10 min | 75% | 12 DASH | 98 | 14.5 | 388 | 2.24 | 59330 | 44798 | 155 | 250 | 14125 | - |

<br/>

## 100_dpns_preorder_per_second_minFill
Registers 30 start identities with 0.4 DASH each and 100 [dpns preorder contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dpns_contract_preorder.json) variants, then submits 1 minimal preorder document per second to all 100 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 19, 2024 | 10 min | 84% | 12 DASH | 98 | 48.6 | 905 | 3.25 | 59330 | 50101 | 3 | 343 | 8875 | - |
| April 17, 2024 | 10 min | 74% | 12 DASH | 97 | 23.1 | 968 | 1.45 | 58830 | 43731 | 0 | 732 | 14352 | - |

<br/>

## 80-dashpay-contactInfo-per_second-minFill
Registers 30 start identities with 0.4 DASH each and 80 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 minimal contactInfo document per second to all 80 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 19, 2024 | 10 min | 99% | 12 DASH | 79 | 21.2 | 388 | 3.05 | 47710 | 47611 | 16 | 60 | 17 | - |

<br/>

## 80_dpns_preorder_per_second_minFill
Registers 30 start identities with 0.3 DASH each and 80 [dpns preorder contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dpns_contract_preorder.json) variants, then submits 1 minimal preorder document per second to all 80 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 19, 2024 | 10 min | 99% | 9 DASH | 78 | 39.4 | 895 | 2.64 | 47390 | 47138 | 2 | 317 | 45 | - |

<br/>

## 50_dashpay_contactInfo_per_second_minFill
Registers 30 start identities with 0.3 DASH each and 50 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 minimal contactInfo document per second to all 50 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 17, 2024 | 10 min | 99% | 9 DASH | 49 | 13.2 | 388 | 2.0 | 29730 | 29460 | 0 | 264 | 0 | - |

<br/>

## 50_dpns_preorder_per_second_minFill
Registers 30 start identities with 0.2 DASH each and 50 [dpns preorder contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dpns_contract_preorder.json) variants, then submits 1 minimal preorder document per second to all 50 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 17, 2024 | 10 min | 99% | 6 DASH | 49 | 28.0 | 968 | 1.7 | 29630 | 29178 | 0 | 452 | 0 | - |
