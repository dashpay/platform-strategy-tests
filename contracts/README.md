# Contract Strategies
Strategies focused on broadcasting contracts.

<br/>

## contract-create-random-10tps-1doctype
Registers 50 start identities with 0.2 DASH each and then 10 random contracts per second with 1 document type each.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit errors | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.11 | 10 min | 98% | 10 DASH | 9 | 9 | 115 | 4.68 | 6009 | 5949 | 50 | 9 | 0 | - |
| v1.0.0-dev.10 | 10 min | 99% | 10 DASH | 10 | 10 | 252 | 2.24 | 5957 | 5873 | 3 | 81 | 0 | - |

<br/>

## contract-create-random-20tps-1doctype
Registers 50 start identities with 0.2 DASH each and then 20 random contracts per second with 1 document type each.

| Version | Run Time | Success Rate | Cost | Avg sent tx/s | Avg mined tx/s | Avg tx/block | Avg blocks/min | Attempt count | Success count | Nonce Errors | Timeout Errors | Rate limit errors | Other errors |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| v1.0.0-dev.10 | 10 min | 30% | 10 DASH | 20 | - | - | - | 11790 | 3673 | 7984 | 217 | 0 | - |
