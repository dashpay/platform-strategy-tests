# Document Strategies
Strategies focused on broadcasting documents.

<br/>

## 100_dashpay_contactInfo_per_second_minFill
Registers 30 start identities with 0.5 DASH each and 100 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 minimal contactInfo document per second to all 100 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 17, 2024 | 10 min | 75% | 15 DASH | 98 | 14.5 | 388 | 2.24 | 59330 | 44798 | 155 | 250 | 14125 | - |

<br/>

## 100_dpns_preorder_per_second_minFill
Registers 30 start identities with 0.5 DASH each and 100 [dpns preorder contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dpns_contract_preorder.json) variants, then submits 1 minimal preorder document per second to all 100 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 17, 2024 | 10 min | 74% | 15 DASH | 97 | 23.1 | 968 | 1.45 | 58830 | 43731 | 0 | 732 | 14352 | - |

<br/>

## 50_dashpay_contactInfo_per_second_minFill
Registers 30 start identities with 0.5 DASH each and 50 [modified dashpay contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dashpay-contract-all-mutable.json) variants, then submits 1 minimal contactInfo document per second to all 50 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 17, 2024 | 10 min | 99% | 15 DASH | 49 | 13.2 | 388 | 2.0 | 29730 | 29460 | 0 | 264 | 0 | - |

<br/>

## 50_dpns_preorder_per_second_minFill
Registers 30 start identities with 0.3 DASH each and 50 [dpns preorder contract](https://github.com/dashpay/rs-platform-explorer/blob/time-based-strategy-execution/supporting_files/contract/dpns_contract_preorder.json) variants, then submits 1 minimal preorder document per second to all 50 contracts.

| Date | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit error | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| April 17, 2024 | 10 min | 99% | 9 DASH | 49 | 28.0 | 968 | 1.7 | 29630 | 29178 | 0 | 452 | 0 | - |
