# Challenge LostWallets

![wallet.dat](https://user-images.githubusercontent.com/82582647/172037651-a03c947c-e51e-4259-80c1-42588bf6d9b7.png)</br>
**Find password get 50% balance**</br>

## How to search for a password
Download the latest version of hashcat [**here**](https://github.com/hashcat/hashcat/releases)</br>
An example of using masks in hashcat is [**here**](https://cheatsheet.haax.fr/passcracking-hashfiles/hashcat_cheatsheet/)</br>
The hashes of the passwords from all wallets is in the file [**hash.txt**](https://github.com/phrutis/LostWallets/blob/main/hash.txt) Update **11.06.2022**</br>

## Example of starting a search
TEST: ```hashcat.exe -m 11300 -a 3 test.txt foot?l?l?l?l -D 2 -w 3 -o FOUND.txt```</br>
Examples:</br>
Run: ```hashcat.exe -m 11300 -a 3 hash.txt ?a?a?a?a?a?a?a?a -D 2 -w 3 -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 7 --increment hash.txt -1 ?l?d ?l?l?l?l?1?1?1?1 prefix.txt -D 2 -w 3 -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 1 hash.txt WORDLIST.txt WORDLIST2.txt -D 2 -w 3 -S -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 3 --increment --increment-min=6 --increment-max=12 hash.txt ?a?a?a?a?a?a?a?a?a?a?a?a -D 2 -w 3 -o FOUND.txt```</br>
Use your password search prefixes by mask or [dictionaries](https://www.weakpass.com/wordlist)</br>

If you manage to find the password, write to me in telegram ```phrutis```</br>
Do not write me questions, look for answers on the [forum](https://hashcat.net/forum/)</br>

- [**Fake Wallets**](https://github.com/phrutis/LostWallets/tree/main/fake-wallets)</br>
- [**Frequently asked Questions**](https://github.com/phrutis/LostWallets#frequently-asked-questions)

### Partner addresses 25%
:one: - 1NEFQpE4qETrAtzzRD8vLGs8FRZmUsV6FF</br>
:two: - bc1qphhedzu5jg7emtw09akwzzdh03mqaytett9zlz</br>
:three: - 1NoName1LLKRfLmoh9jawLWrf6t185bC7v</br>
:four: - bc1q5k000jhfklq8k82lpf8fz9cwffj4murvt7kxpm</br>
:five: - bc1qgdgr02whvzkzqcqhpstqepq8sjcc4ljgyfnka9</br>
:six: - 13npiGYMZVqYiRJ9Xr2vTu8NAmzCQ1iCGv</br>
:seven: - 1BGYYSyPbs4YFDDudAVAULpNdkJQbYQpaS</br>
:eight: - 1LcFtZjX3U8EX7pgYiawphmzyM9SYrq5z5</br>
:nine: - 15sxxBRF2Lvutzf92UK2Jqzm4MzwkukFFc</br>
:keycap_ten: - bc1qcqsdeyfygy8trg7gfyqz3x5nds06d9vmzftcka

# Tables in the process of updating...

|  Wallet name    | Address  | Hunter |  | Partner | Update |
|:----------------|:---------|:-------|:-|:--------|:-------|
| 12600.dat | [252 addresses](https://github.com/phrutis/LostWallets/blob/main/empty/12600.txt) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 10000.00417651.dat | [1LfV1tSt3KNyHpFJnAzrqsLFdeD2EvU1MK](https://www.blockchain.com/btc/address/1LfV1tSt3KNyHpFJnAzrqsLFdeD2EvU1MK) | 50% | :lock: | :three: | 09.06.2022 |
| 7941.06429735.dat | [15Z5YJaaNSxeynvr6uW6jQZLwq3n1Hu6RX](https://www.blockchain.com/btc/address/15Z5YJaaNSxeynvr6uW6jQZLwq3n1Hu6RX) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 4000.dat | [18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM](https://www.blockchain.com/btc/address/18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM) | 50% | :lock: | :two: | 09.06.2022 |
| 4000.00222015.dat | [18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM](https://www.blockchain.com/btc/address/18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM) | 50% | :lock: | :two:  | 03.06.2022 |
| 2026.46416785.dat | [14 addresses](https://github.com/phrutis/LostWallets/blob/main/empty/2026.46416785.txt) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 1550.dat | [31 addresses](https://github.com/phrutis/LostWallets/blob/main/empty/1550.txt) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 1545.dat | [12yqUYtcCvDgiDgzJTT7DsSCoSifwYavhH](https://www.blockchain.com/btc/address/12yqUYtcCvDgiDgzJTT7DsSCoSifwYavhH) + [440](https://www.blockchain.com/btc/address/1PUfK6ecmFiV1sf7TppFfdCsTZw6PyK8Xu) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 1500.dat | [15 addresses](https://github.com/phrutis/LostWallets/blob/main/empty/1500.txt) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 1434.80211957.dat | [1D6iTqvbgcqenbkKNsFsi9zN21KH4KPPEa](https://www.blockchain.com/btc/address/1D6iTqvbgcqenbkKNsFsi9zN21KH4KPPEa) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 1240.00169821.dat | [1FmLMbBLwJrnm3giK69WtKrH9yQZqecDjD](https://www.blockchain.com/btc/address/1FmLMbBLwJrnm3giK69WtKrH9yQZqecDjD) + [420](https://www.blockchain.com/btc/address/1DEfMuUGRhvoQE7cxgds3nYjRZzzhfJ9jc) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 1128.77038444.dat | [12At4GGP8J5p4MtdjNy1SPSkqKEM1mw2FS](https://www.blockchain.com/btc/address/12At4GGP8J5p4MtdjNy1SPSkqKEM1mw2FS) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 875.00062957.dat | [16mEzobs4wQPuAMq1C8QSQafcDHvzczVcs](https://www.blockchain.com/btc/address/16mEzobs4wQPuAMq1C8QSQafcDHvzczVcs) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 861.87860297.dat | [15mkHA8s76bk3Z8ohxF4FSwui1Xs8dGxvH](https://www.blockchain.com/btc/address/15mkHA8s76bk3Z8ohxF4FSwui1Xs8dGxvH) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 624.85723967.dat | [484](https://www.blockchain.com/btc/address/12m9dz42JrwCwLhxuzVMzNs9BXvwxTp3B1) + [112](https://www.blockchain.com/btc/address/1ETfw6xXhVsYEKisrBLGjtNq1nZWT7YsD5) + [28](https://www.blockchain.com/btc/address/1DLGk1s8FBjMrS7nge8178QAQTB1rKRLLi) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 568.23062504.dat | [1ZhKkzRLLfpNGNHf8qDDH7uRZtaMue7tR](https://www.blockchain.com/btc/address/1ZhKkzRLLfpNGNHf8qDDH7uRZtaMue7tR) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 575.99105683.dat | [1HZNsUqQxKVLmfPfCAzLwrnVDzx8CxwxnM](https://www.blockchain.com/btc/address/1HZNsUqQxKVLmfPfCAzLwrnVDzx8CxwxnM) | 50% | :lock: | :six: | 24.06.2022 |
| 551.16886507.dat | [12yqLsUvrULLvejhJMWnTcEQ7xhHCoSEGC](https://www.blockchain.com/btc/address/12yqLsUvrULLvejhJMWnTcEQ7xhHCoSEGC) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 478.33.dat | [11.10](https://www.blockchain.com/btc/address/1QBMmD24baHgusrqUSXc9s1uALtHeuJsjK) + [203.50](https://www.blockchain.com/btc/address/1NUnbngzRB2SeMqZLrLrypoYW5FrusVU3X) + [76.70](https://www.blockchain.com/btc/address/1JXvzLcpxh3LBvEi1NKE6qAVpft6khkpWN) + [103.78](https://www.blockchain.com/btc/address/1A6R1sEkzpkNPx5hdJHjmN3947qYXFxuHz) + [83.25](https://www.blockchain.com/btc/address/187oyQbBSRx8azGY8EC3V9oTsm6bTD45Zb) | 50% | :lock: | :one: | 09.06.2022 |
| 405.00120319.dat | [1An4jHFsSz31TjW49vsZtCt2SXKV7oHRWb](https://www.blockchain.com/btc/address/1An4jHFsSz31TjW49vsZtCt2SXKV7oHRWb) | 50% | :lock: | :one: | 09.06.2022 |
| 340.00283740.dat | [1JqPFnGPhHhy54zJKmC1MPiczzgFjCmzE9](https://www.blockchain.com/btc/address/1JqPFnGPhHhy54zJKmC1MPiczzgFjCmzE9) | 50% | :lock: | :one: | 09.06.2022 |
| 319.00053581.dat | [1FJBeYLRArReqVTiqwYTEc9hAfypGx8MyN](https://www.blockchain.com/btc/address/1FJBeYLRArReqVTiqwYTEc9hAfypGx8MyN) | 50% | :lock: | :one: | 09.06.2022 |
| 300.00055278.dat | [1LbvdyYr5KH8fZhXJ7txBr1RjoDnzhQEqY](https://www.blockchain.com/btc/address/1LbvdyYr5KH8fZhXJ7txBr1RjoDnzhQEqY) | 50% | :lock: | :one: | 09.06.2022 |
| 252.20004225.dat | [1GYLfNfMesF3YrwVU94P5wtcJjhAx9DLYy](https://www.blockchain.com/btc/address/1GYLfNfMesF3YrwVU94P5wtcJjhAx9DLYy) | 50% | :lock: | :one: | 05.06.2022 |
| 200.00224825.dat | [1DDYt8kJE1JBa2kQN1R921weJGbCnWcgG4](https://www.blockchain.com/btc/address/1DDYt8kJE1JBa2kQN1R921weJGbCnWcgG4) | 50% | :lock: | :one: | 09.06.2022 |
| 198.00412439.dat | [1E87cVPLZ938w7vYEA1e9RWSc8mESPA3J5](https://www.blockchain.com/btc/address/1E87cVPLZ938w7vYEA1e9RWSc8mESPA3J5) | 50% | :lock: | :one: | 09.06.2022 |
| 186.29379209.dat | [16vMxeMHJDbMoDu2s1ozDQAmzY3bPmdLLi](https://www.blockchain.com/btc/address/16vMxeMHJDbMoDu2s1ozDQAmzY3bPmdLLi) | 50% | :lock: | :three: | 09.06.2022 |
| 180.77714198.dat | [1DCqdVEh91bVzEShe6iU5iuNrd1LbsWvgf](https://www.blockchain.com/btc/address/1DCqdVEh91bVzEShe6iU5iuNrd1LbsWvgf) | 50% | :lock: | :one: | 09.06.2022 |
| 177.74326390.dat | [1BiA2yvL3GWuGGVr7v1cGCbH6WPYvoG4tL](https://www.blockchain.com/btc/address/1BiA2yvL3GWuGGVr7v1cGCbH6WPYvoG4tL) | 50% | :lock: | :three: | 09.06.2022 |
| 169.00013592.dat | [1GthMXgwcHByL4ZNXVJn92ax6LN5RJYRK3](https://www.blockchain.com/btc/address/1GthMXgwcHByL4ZNXVJn92ax6LN5RJYRK3) | 50% | :lock: | :six: | 24.06.2022 |
| 167.00093679.dat | [1Edi4uNFiR3R2Tw96MU3bLi7ZFtBsihNpY](https://www.blockchain.com/btc/address/1Edi4uNFiR3R2Tw96MU3bLi7ZFtBsihNpY) | 50% | :lock: | :seven: | 19.07.2022 |
| 159.89913129.dat | [12PpzLTHNWCLsHPgHMNd9ebj7bwbTxs33u](https://www.blockchain.com/btc/address/12PpzLTHNWCLsHPgHMNd9ebj7bwbTxs33u) | 50% | :lock: | :one: | 11.06.2022 |
| 151.00001435.dat | [12u6hecWRHEPceLYZ9yhubZvhgKYuLGf1J](https://www.blockchain.com/btc/address/12u6hecWRHEPceLYZ9yhubZvhgKYuLGf1J) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 150.05001641.dat | [100](https://www.blockchain.com/btc/address/12spqcvLTFhL38oNJDDLfW1GpFGxLdaLCL) + [50](https://www.blockchain.com/btc/address/1378aLQwg3GXJ5x3H4u13bA5kYN6taQcSt) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 146.05083427.dat | [138](https://www.blockchain.com/btc/address/1223QsgwzkPZTfndWSFYCM3mHWxMti9FC3) + [7](https://www.blockchain.com/btc/address/1Fboq3tUgM1Fgwp1VbMU9vLGGiCuu6RQCu) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 141.01102103.dat | [12qGjvgbRDePYt9n6D1F64Zn2dT6JtUgm9](https://www.blockchain.com/btc/address/12qGjvgbRDePYt9n6D1F64Zn2dT6JtUgm9) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 140.41719437.dat | [15JVDn2Uz6gf2C1vbeYWwgVP476VdVmoRU](https://www.blockchain.com/btc/address/15JVDn2Uz6gf2C1vbeYWwgVP476VdVmoRU) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 131.63.dat | [31.63](https://www.blockchain.com/btc/address/1EZeYuLR2ugK8sk4XeDVcyNGBT7sGPDrNb) + [50.00](https://www.blockchain.com/btc/address/1DFo9TYjyKT7Rwa1Nx7G3STMRHBFUC2hUB) + [50.00](https://www.blockchain.com/btc/address/1EdrQwSXQYFKZKim3fX7jKTiR5gmjsjT64) | 50% | :lock: | :four: | 09.06.2022 |
| 130.00000547.dat | [1P2kKdepEAJQwVHoaodfQKD6jSJC86z1Yw](https://www.blockchain.com/btc/address/1P2kKdepEAJQwVHoaodfQKD6jSJC86z1Yw) | 50% | :lock: | :one: | 09.06.2022 |
| 129.66226125.dat | [1AamCcS7oXPZYvYw7dwcZxjxJkPSxZ94vm](https://www.blockchain.com/btc/address/1AamCcS7oXPZYvYw7dwcZxjxJkPSxZ94vm) | 50% | :lock: | :one: | 09.06.2022 |
| 120.36895547.dat | [12qj1UiJA2hantqbairCV4mVQFnVYDqjix](https://www.blockchain.com/btc/address/12qj1UiJA2hantqbairCV4mVQFnVYDqjix) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 108.88970547.dat | [12SrgFEagZfNqWkccZAJzgMXn4tnaGGLmw](https://www.blockchain.com/btc/address/12SrgFEagZfNqWkccZAJzgMXn4tnaGGLmw) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 108.06001094.dat | [1G3hJ3CJdovXiTyK1AWQpTevW1hHCQ7jsM](https://www.blockchain.com/btc/address/1G3hJ3CJdovXiTyK1AWQpTevW1hHCQ7jsM) | 50% | :lock: | :one: | 09.06.2022 |
| 108.06001094-2.dat | [1G3hJ3CJdovXiTyK1AWQpTevW1hHCQ7jsM](https://www.blockchain.com/btc/address/1G3hJ3CJdovXiTyK1AWQpTevW1hHCQ7jsM) | 50% | :lock: | :one: | 09.06.2022 |
| 106.96263501.dat | [79](https://www.blockchain.com/btc/address/12KjyrdtVQkEihGpWcb7WUw9JHGjq3D2Mt) + [15](https://www.blockchain.com/btc/address/16MW99tMjWMe6sVXXeEG1WEfFsem8WMi66) + [12](https://www.blockchain.com/btc/address/17mXT5qQWECEjqvK1fD1SiMYTJ87G7AojY)| 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 105.11031599.dat | [52.97191089](https://www.blockchain.com/btc/address/15wx2WPf67P9AqrMUPzcePzzDFa7pJmhud) + [52.13840510](https://www.blockchain.com/btc/address/1GtR4VXdRNMqnABAiAgGYnB4yQyWZ2ZTWk) | 50% | :lock: | :one: | 09.06.2022 |
| 101.10432862.dat | [12ZHXg2UirjwWMPgzFaNTzX7CeQWPZnc66](https://www.blockchain.com/btc/address/12ZHXg2UirjwWMPgzFaNTzX7CeQWPZnc66) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 100.63001641.dat | [123DL94r8WutV42Ftoy2zU9o4zZor9h5aJ](https://www.blockchain.com/btc/address/123DL94r8WutV42Ftoy2zU9o4zZor9h5aJ) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 100.42001094.dat | [1J6PkJqgCXvH3YHdcmd7pEi63NwoW8RJHv](https://www.blockchain.com/btc/address/1J6PkJqgCXvH3YHdcmd7pEi63NwoW8RJHv) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 101.00101641.dat | [12sacHekno37tgdvZhFe6P1wbcSsHg2vXH](https://www.blockchain.com/btc/address/12sacHekno37tgdvZhFe6P1wbcSsHg2vXH) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 100.00018136.dat | [133fZZzNNbHL5VSuCWrUkLW2oL9ZPJELbY](https://www.blockchain.com/btc/address/133fZZzNNbHL5VSuCWrUkLW2oL9ZPJELbY) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 100.00000547.dat | [12uGriNcYtJqFB7f3tCLK12HPTTZ5eKmz2](https://www.blockchain.com/btc/address/12uGriNcYtJqFB7f3tCLK12HPTTZ5eKmz2) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 99.99901094.dat | [1Gj2KiTy9SFtuFSJECmpePseYchhkU3gXQ](https://www.blockchain.com/btc/address/1Gj2KiTy9SFtuFSJECmpePseYchhkU3gXQ) | 50% | :lock: | :four: | 09.06.2022 |
| 99.99601641.dat | [15Q6F5CwYCziQ14kR3zCdxeWkfExvfQr6T](https://www.blockchain.com/btc/address/15Q6F5CwYCziQ14kR3zCdxeWkfExvfQr6T) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 99.46510547.dat | [12wfJ3uXk35BhahmAKQd91ZABjHWA1xFqE](https://www.blockchain.com/btc/address/12wfJ3uXk35BhahmAKQd91ZABjHWA1xFqE) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 91.00501641.dat | [1BvNsod2wBpjoJmYmbnhk1j9FLLWz7HzZE](https://www.blockchain.com/btc/address/1BvNsod2wBpjoJmYmbnhk1j9FLLWz7HzZE) | 50% | :lock: | :one: | 09.06.2022 |
| 90.59781094.dat | [73.50781094](https://www.blockchain.com/btc/address/18EGA8nGHjA998Qc17je6K8T6UUDHxeoCH) + [17.09000000](https://www.blockchain.com/btc/address/182RVphMRdEe9i5A4EikLx8RH1EenFBeCG) | 50% | :lock: | :five: | 09.06.2022 |
| 89.50001641.dat | [12BJ6VvZTPRT3MuJTxCVTwHCbdAbxTFMSD](https://www.blockchain.com/btc/address/12BJ6VvZTPRT3MuJTxCVTwHCbdAbxTFMSD) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 89.00001641.dat | [12Zxj2AFMumrTgFZzfcT7iAtNSafGRJRTg](https://www.blockchain.com/btc/address/12Zxj2AFMumrTgFZzfcT7iAtNSafGRJRTg) | 50% | :lock: |  :keycap_ten: | 08.09.2022 |
| 87.86507229.dat | [1PYeoCUYbq6zsh7BcyRgeAQdkFGnhCY95T](https://www.blockchain.com/btc/address/1PYeoCUYbq6zsh7BcyRgeAQdkFGnhCY95T) | 50% | :lock: | :one: | 09.06.2022 |
| 86.63001094.dat | [161vuWHBD8LcNdr28QjKu2SbADyknBEVGv](https://www.blockchain.com/btc/address/161vuWHBD8LcNdr28QjKu2SbADyknBEVGv) + [36](https://www.blockchain.com/btc/address/13KXcGDFXxcFvmUwmqSVj7o7df8oNEDFSf) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 78.65929782.dat | [1Pq2Y45aDfwGn6pKFGv8enKgNR2efw4jFW](https://www.blockchain.com/btc/address/1Pq2Y45aDfwGn6pKFGv8enKgNR2efw4jFW) | 50% | :lock: | :three: | 09.06.2022 |
| 78.60361094.dat | [1BSmyTdYpsHA5JhLS9azGmVADuJRiLWE5Z](https://www.blockchain.com/btc/address/1BSmyTdYpsHA5JhLS9azGmVADuJRiLWE5Z) | 50% | :lock: | :one: | 09.06.2022 |
| 77.98600547.dat | [14tZU9KyHXwkGXkVUKehkMfaEZ8ad7jwNc](https://www.blockchain.com/btc/address/14tZU9KyHXwkGXkVUKehkMfaEZ8ad7jwNc) | 50% | :lock: | :one: | 09.06.2022 |
| 76.85957756.dat | [1Eub69pJHFr3GoBfDiGQvxrDEPmL3gMmMT + 3](https://www.blockchain.com/btc/address/1Eub69pJHFr3GoBfDiGQvxrDEPmL3gMmMT) | 50% | :lock: | :nine: | 30.08.2022 |
| 75.25000000.dat | [25](https://www.blockchain.com/btc/address/1NVa46rWpm6j33fDvvcfJ1GEzJKh9MP7RX) + [25](https://www.blockchain.com/btc/address/18NxttmXTJfifBJCeJnJYTVvTniR5hZRBB) + [25](https://www.blockchain.com/btc/address/19C1pbZioNsmzUCHRic66NRum9RkqQF3P6)| 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 75.00011094.dat | [1Afh86YLq9tZWGsQhmDvCoGE2QhwYXxmcY](https://www.blockchain.com/btc/address/1Afh86YLq9tZWGsQhmDvCoGE2QhwYXxmcY) + [25](https://www.blockchain.com/btc/address/12BycRrxPivnhnwfD5qfKaE7ccAc1qhrCb) | 50% | :lock: | :six: | 24.06.2022 |
| 74.16883731.dat | [1F11GQNQKTEme6L74c5dVTTMkD7ME2jiqP](https://www.blockchain.com/btc/address/1F11GQNQKTEme6L74c5dVTTMkD7ME2jiqP) | 50% | :lock: | :one: | 09.06.2022 |
| 73.50781094.dat | [18EGA8nGHjA998Qc17je6K8T6UUDHxeoCH](https://www.blockchain.com/btc/address/18EGA8nGHjA998Qc17je6K8T6UUDHxeoCH) | 50% | :lock: | :one: | 09.06.2022 |
| 67.82951641.dat | [1Lvs4iij3hkMasDBENCNqgdTb3f3BXbUEL](https://www.blockchain.com/btc/address/1Lvs4iij3hkMasDBENCNqgdTb3f3BXbUEL) + [37](https://www.blockchain.com/btc/address/18XNHa8aLpmxmJJFvf2QjNa638U691TC6W)| 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 67.28898471.dat | [13AP4J1bE348USwHcaY3c846PdA31RCHeh](https://www.blockchain.com/btc/address/13AP4J1bE348USwHcaY3c846PdA31RCHeh) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 64.30251094.dat | [1LRc9XLxZbDrHDEagHPESdxbzm798HMek2](https://www.blockchain.com/btc/address/1LRc9XLxZbDrHDEagHPESdxbzm798HMek2) | 50% | :lock: | :six: | 24.06.2022 |
| 63.10894284.dat | [1LWRBFB9u9oCDuawjGUrr1RoyFXhhZvoXb](https://www.blockchain.com/btc/address/1LWRBFB9u9oCDuawjGUrr1RoyFXhhZvoXb) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 62.80100547.dat | [12bQpYge7nBajDzyTVhGXJiwmoUKwUwDYZ](https://www.blockchain.com/btc/address/12bQpYge7nBajDzyTVhGXJiwmoUKwUwDYZ) | 50% | :lock: | :keycap_ten: | 08.09.2022 |
| 52.55001760.dat | [13KKv3ywwJ5WYovLgiCAaqpCVuMDEF6oxo](https://www.blockchain.com/btc/address/13KKv3ywwJ5WYovLgiCAaqpCVuMDEF6oxo) | 50% | :lock: | :one: | 09.06.2022 |
| 52.08001094.dat | [15Ybt9WjCF5ABAZ1GjFVTjzV3dJH5f9USh](https://www.blockchain.com/btc/address/15Ybt9WjCF5ABAZ1GjFVTjzV3dJH5f9USh) | 50% | :lock: | :one: | 09.06.2022 |
| 50.43201094.dat | [1QFDAGXRkhNYfx2mHEu81QH8dAj4go4A8d](https://www.blockchain.com/btc/address/1QFDAGXRkhNYfx2mHEu81QH8dAj4go4A8d) | 50% | :lock: | :one: | 09.06.2022 |
| 50.18338758.dat | [1NyEeyXu8ydNw67e3ZTUmkwQJ8QNd1o3cF](https://www.blockchain.com/btc/address/1NyEeyXu8ydNw67e3ZTUmkwQJ8QNd1o3cF) | 50% | :lock: | :three: | 09.06.2022 |
| 50.00011641.dat | [1MtXD6gGHZB1cAcP1Du29Ho9KobMCYD7ZC](https://www.blockchain.com/btc/address/1MtXD6gGHZB1cAcP1Du29Ho9KobMCYD7ZC) | 50% | :lock: | :three: | 09.06.2022 |
| 50.00004046.dat | [13vq3LDCBpwbyxSenJDpHWt3xCXgbtzp9V](https://www.blockchain.com/btc/address/13vq3LDCBpwbyxSenJDpHWt3xCXgbtzp9V) | 50% | :lock: | :four: | 09.06.2022 |
| 50.00003282.dat | [1E4ad5bA8HgbqxsPYpmDtVRNBRF2XfqTns](https://www.blockchain.com/btc/address/1E4ad5bA8HgbqxsPYpmDtVRNBRF2XfqTns) | 50% | :lock: | :one: | 09.06.2022 |
| 50.00002188.dat | [1KTvsW5tg5gkJf9fyT2xsvjkv7dzuZNTpW](https://www.blockchain.com/btc/address/1KTvsW5tg5gkJf9fyT2xsvjkv7dzuZNTpW) | 50% | :lock: | :one: | 09.06.2022 |
| 50.00001641.dat | [1JHqAnwohyhXgvwNnzEMeMwejsf6vHZhgp](https://www.blockchain.com/btc/address/1JHqAnwohyhXgvwNnzEMeMwejsf6vHZhgp) | 50% | :lock: | :four: | 09.06.2022 |
| 50.00001641-2.dat | [18h7ETAzcqRCGNXTstWSavrvhy5S5YKsQF](https://www.blockchain.com/btc/address/18h7ETAzcqRCGNXTstWSavrvhy5S5YKsQF) | 50% | :lock: | :four: | 09.06.2022 |
| 50.00000547.dat | [1Aw6miK9me2AijQ76Q32NkPa1B7buWqWPg](https://www.blockchain.com/btc/address/1Aw6miK9me2AijQ76Q32NkPa1B7buWqWPg) | 50% | :lock: | :one: | 09.06.2022 |
| 48.92440002.dat | [18rB6Uh5tGTu1TftZ8swNgzp9DtieJaWhz](https://www.blockchain.com/btc/address/18rB6Uh5tGTu1TftZ8swNgzp9DtieJaWhz) | 50% | :lock: | :one: | 09.06.2022 |
| 47.00001094.dat | [18HYU4HJe6h4ETeG1N7GUANFoKoqME2JYT](https://www.blockchain.com/btc/address/18HYU4HJe6h4ETeG1N7GUANFoKoqME2JYT) | 50% | :lock: | :six: | 24.06.2022 |
| 42.53718329.dat | [1NKmf6GszBQ6wo349LUT4Je1csNyDDpb5Y](https://www.blockchain.com/btc/address/1NKmf6GszBQ6wo349LUT4Je1csNyDDpb5Y) | 50% | :lock: | :three: | 09.06.2022 |
| 34.77568617.dat | [1GnNo5yKUiPoHY3Lo67nNYEMgHRDxaNEo2](https://www.blockchain.com/btc/address/1GnNo5yKUiPoHY3Lo67nNYEMgHRDxaNEo2) | 50% | :lock: | :eight: | 01.08.2022 |
| 32.85679433.dat | [15r2tRv6B47zGFrCFsUSxtGtxxKVN6KAUc](https://www.blockchain.com/btc/address/15r2tRv6B47zGFrCFsUSxtGtxxKVN6KAUc) | 50% | :lock: | :one: | 09.06.2022 |
| 31.63000580.dat | [1EZeYuLR2ugK8sk4XeDVcyNGBT7sGPDrNb](https://www.blockchain.com/btc/address/1EZeYuLR2ugK8sk4XeDVcyNGBT7sGPDrNb) | 50% | :lock: | :four: | 09.06.2022 |
| 31.01002188.dat | [14J2wsejqNKtrEpAe1ziQVHQHFE3yX6bKB](https://www.blockchain.com/btc/address/14J2wsejqNKtrEpAe1ziQVHQHFE3yX6bKB) | 50% | :lock: | :three: | 09.06.2022 |
| 30.99098222.dat | [18jANvQ6AuVGJnea4EhmXiAf6bHR5qKjPB](https://www.blockchain.com/btc/address/18jANvQ6AuVGJnea4EhmXiAf6bHR5qKjPB) | 50% | :lock: | :three: | 09.06.2022 |
| 28.00001000.dat | [1PbHeg1WDosvuhApxbfQg3iFDQ2WW7Mttf](https://www.blockchain.com/btc/address/1PbHeg1WDosvuhApxbfQg3iFDQ2WW7Mttf) | 50% | :lock: | :three: | 09.06.2022 |
| 27.03768216.dat | [1rhYqDz3WEbCSQM54bGguTnJkmLQwV3d5](https://www.blockchain.com/btc/address/1rhYqDz3WEbCSQM54bGguTnJkmLQwV3d5) | 50% | :lock: | :three: | 09.06.2022 |
| 25.99960547.dat | [1JSTCtS21CFqBz2ZQT4X9sTeCoy58FwtDj](https://www.blockchain.com/btc/address/1JSTCtS21CFqBz2ZQT4X9sTeCoy58FwtDj) | 50% | :lock: | :three: | 09.06.2022 |
| 25.00101641.dat | [14PcoSTA1g2k1t2W5jg1S9zc5Si8ToQxke](https://www.blockchain.com/btc/address/14PcoSTA1g2k1t2W5jg1S9zc5Si8ToQxke) | 50% | :lock: | :one: | 09.06.2022 |
| 22.85001641.dat | [19Hj5Pzi4hCj12porw97i183XYTrScbtXS](https://www.blockchain.com/btc/address/19Hj5Pzi4hCj12porw97i183XYTrScbtXS) | 50% | :lock: | :three: | 09.06.2022 |
| 21.89679859.dat | [1HBXJBXWYM1jZd8p1ff2a4uhJxvtgoXiYU](https://www.blockchain.com/btc/address/1HBXJBXWYM1jZd8p1ff2a4uhJxvtgoXiYU) | 50% | :lock: | :one: | 09.06.2022 |
| 20.11001641.dat | [1NuPEefRU2AZ319x45fY5wBHBV2Z72PY98](https://www.blockchain.com/btc/address/1NuPEefRU2AZ319x45fY5wBHBV2Z72PY98) | 50% | :lock: | :one: | 09.06.2022 |
| 20.00241094.dat | [1F3yxoWp5TdpVzbziVJ2VnvhpaXJma3qnF](https://www.blockchain.com/btc/address/1F3yxoWp5TdpVzbziVJ2VnvhpaXJma3qnF) | 50% | :lock: | :one: | 09.06.2022 |
| 19.88790000.dat | [19hZHgZt94uXxSJhWDqxMpEZmN3ctvVFvH](https://www.blockchain.com/btc/address/19hZHgZt94uXxSJhWDqxMpEZmN3ctvVFvH) | 50% | :lock: | :one: | 09.06.2022 |
| 19.43300547.dat | [18H3tXBX9fC2AguKV2m34YKHYugN1Y4XkA](https://www.blockchain.com/btc/address/18H3tXBX9fC2AguKV2m34YKHYugN1Y4XkA) | 50% | :lock: | :one: | 09.06.2022 |
| 19.33608000.dat | [1HuTxwnZMyaNRTsHJ2Xg83Z7mt75dtdwC3](https://www.blockchain.com/btc/address/1HuTxwnZMyaNRTsHJ2Xg83Z7mt75dtdwC3) | 50% | :lock: | :one: | 09.06.2022 |
| 19.30000000.dat | [18HKjVPJwfDg7TDSpoVh2KBiTQny6hymMX](https://www.blockchain.com/btc/address/18HKjVPJwfDg7TDSpoVh2KBiTQny6hymMX) | 50% | :lock: | :one: | 09.06.2022 |
| 19.28011668.dat | [1EREjjsLgB5JJQhN89gQR9PvH89yWJ4kuV](https://www.blockchain.com/btc/address/1EREjjsLgB5JJQhN89gQR9PvH89yWJ4kuV) | 50% | :lock: | :one: | 09.06.2022 |
| 18.72704494.dat | [1LSmeqqYoyGAxUwLxmkvuDU6LGM2FGf6AS](https://www.blockchain.com/btc/address/1LSmeqqYoyGAxUwLxmkvuDU6LGM2FGf6AS) | 50% | :lock: | :one: | 09.06.2022 |
| 18.17000000.dat | [1EM7FJV7L3CJZuH6SFTpYnmbMi9RXKdwK6](https://www.blockchain.com/btc/address/1EM7FJV7L3CJZuH6SFTpYnmbMi9RXKdwK6) | 50% | :lock: | :three: | 09.06.2022 |
| 18.00000000.dat | [1B5FuKQgmPg4SJsCjFU3svrFPpZpQZMU1d](https://www.blockchain.com/btc/address/1B5FuKQgmPg4SJsCjFU3svrFPpZpQZMU1d) | 50% | :lock: | :one: | 09.06.2022 |
| 17.82900000.dat | [1LwQU2kqdH6dLSsizstNxrhqk7XhCMLMF3](https://www.blockchain.com/btc/address/1LwQU2kqdH6dLSsizstNxrhqk7XhCMLMF3) | 50% | :lock: | :four: | 09.06.2022 |
| 17.82021465.dat | [17ixLGdJQDdS76Un535rzbtxJNjmAJFqac](https://www.blockchain.com/btc/address/17ixLGdJQDdS76Un535rzbtxJNjmAJFqac) | 50% | :lock: | :one: | 09.06.2022 |
| 17.20100000.dat | [13q3UMbUdqak1xX385aZc3MmtdMtNfsnSU](https://www.blockchain.com/btc/address/13q3UMbUdqak1xX385aZc3MmtdMtNfsnSU) | 50% | :lock: | :one: | 09.06.2022 |
| 17.19060793.dat | [1LJxQSJ1uf2VHq4RDZgHQgEwn8JRAr6btq](https://www.blockchain.com/btc/address/1LJxQSJ1uf2VHq4RDZgHQgEwn8JRAr6btq) | 50% | :lock: | :one: | 09.06.2022 |
| 17.09000666.dat | [1NFp8YqgBjSRFdgWt7ynmojG8gpQDjVDpJ](https://www.blockchain.com/btc/address/1NFp8YqgBjSRFdgWt7ynmojG8gpQDjVDpJ) | 50% | :lock: | :one: | 09.06.2022 |
| 17.08998980.dat | [16Wi4S2Dn9sK2VVtP5EgA3UP1zEry6oY8X](https://www.blockchain.com/btc/address/16Wi4S2Dn9sK2VVtP5EgA3UP1zEry6oY8X) | 50% | :lock: | :one: | 09.06.2022 |
| 16.23030002.dat | [15npoeYGso1qyFAo7Wzw35s4fXMDh5ryrj](https://www.blockchain.com/btc/address/15npoeYGso1qyFAo7Wzw35s4fXMDh5ryrj) | 50% | :lock: | :one: | 09.06.2022 |
| 16.13643422.dat | [14jt9AzqeM1TX3oQCGWkQbtfeUYih3o56W](https://www.blockchain.com/btc/address/14jt9AzqeM1TX3oQCGWkQbtfeUYih3o56W) | 50% | :lock: | :one: | 09.06.2022 |
| 15.99100158.dat | [12ie6iDXeyBcyjSgdrs8Jo5eUbHg4r2N7Q](https://www.blockchain.com/btc/address/12ie6iDXeyBcyjSgdrs8Jo5eUbHg4r2N7Q) | 50% | :lock: | :three: | 09.06.2022 |
| 15.75044635.dat | [1H9WV22GeCQuTGQbwTEQfGZhvTVhNsscNr](https://www.blockchain.com/btc/address/1H9WV22GeCQuTGQbwTEQfGZhvTVhNsscNr) | 50% | :lock: | :one: | 09.06.2022 |
| 15.71719998.dat | [1Lefr9kXBybeW4SG1KtpysnnKKftnDYTvP](https://www.blockchain.com/btc/address/1Lefr9kXBybeW4SG1KtpysnnKKftnDYTvP) | 50% | :lock: | :one: | 09.06.2022 |
| 15.01812238.dat | [18snvPxfy9SGZUNe9i7kUJced3PEdVWodm](https://www.blockchain.com/btc/address/18snvPxfy9SGZUNe9i7kUJced3PEdVWodm) | 50% | :lock: | :one: | 09.06.2022 |
| 14.77500000.dat | [1LhKQqkjzxxzve61HYytPYJ7oVMh88aV4T](https://www.blockchain.com/btc/address/1LhKQqkjzxxzve61HYytPYJ7oVMh88aV4T) | 50% | :lock: | :one: | 09.06.2022 |
| 14.70456309.dat | [1AHgGcw8LjzhsRKtKxjvyRSUSAnkcAEMjX](https://www.blockchain.com/btc/address/1AHgGcw8LjzhsRKtKxjvyRSUSAnkcAEMjX) | 50% | :lock: | :one: | 09.06.2022 |
| 14.60000000.dat | [15LhbzoCjr9icNTsabMVBKCgTZYqPHgcaf](https://www.blockchain.com/btc/address/15LhbzoCjr9icNTsabMVBKCgTZYqPHgcaf) | 50% | :lock: | :one: | 09.06.2022 |
| 14.35226342.dat | [1AYyMBbxXv9E29qJoTpbd6ocje81ZAJQsF](https://www.blockchain.com/btc/address/1AYyMBbxXv9E29qJoTpbd6ocje81ZAJQsF) | 50% | :lock: | :three: | 09.06.2022 |
| 14.09013974.dat | [1GDcVTrZNhVFt7pEnwvHfepoth6mqHVVvq](https://www.blockchain.com/btc/address/1GDcVTrZNhVFt7pEnwvHfepoth6mqHVVvq) | 50% | :lock: | :four: | 09.06.2022 |
| 14.00010000.dat | [177a2RmG1nn78BQpjAyuEztvv24dXdns7r](https://www.blockchain.com/btc/address/177a2RmG1nn78BQpjAyuEztvv24dXdns7r) | 50% | :lock: | :one: | 09.06.2022 |
| 14.00001641.dat | [1JHwt6ArhujJmgDKPtSmGkMmSAPyAhVptL](https://www.blockchain.com/btc/address/1JHwt6ArhujJmgDKPtSmGkMmSAPyAhVptL) | 50% | :lock: | :six: | 24.06.2022 |
| 13.76858117.dat | [1LmdsdywkMNqgXg7x7q88NT2WeXXf52co3](https://www.blockchain.com/btc/address/1LmdsdywkMNqgXg7x7q88NT2WeXXf52co3) | 50% | :lock: | :one: | 09.06.2022 |
| 13.47094589.dat | [1DphS33aWDZBWNEh3rPJFfD6GFP1mmgerU](https://www.blockchain.com/btc/address/1DphS33aWDZBWNEh3rPJFfD6GFP1mmgerU) | 50% | :lock: | :one: | 09.06.2022 |
| 12.82192064.dat | [19tLSCZWhX5YBVy6uX2kLheNjdUb9RBojS](https://www.blockchain.com/btc/address/19tLSCZWhX5YBVy6uX2kLheNjdUb9RBojS) | 50% | :lock: | :one: | 09.06.2022 |
| 10.83091000.dat | [1MB28otoAQFpP9ywiA8CbYVSKHpSTBH1z6](https://www.blockchain.com/btc/address/1MB28otoAQFpP9ywiA8CbYVSKHpSTBH1z6) | 50% | :lock: | :three: | 09.06.2022 |
| 10.50200000.dat | [14PEUoKuRB9Q7yfS94cRXh2XugsrBxbxAo](https://www.blockchain.com/btc/address/14PEUoKuRB9Q7yfS94cRXh2XugsrBxbxAo) | 50% | :lock: | :three: | 09.06.2022 |
| 10.21000001.dat | [1L3amZhWgU8vnGzeMKJc4QFqvQhpU53WsV](https://www.blockchain.com/btc/address/1L3amZhWgU8vnGzeMKJc4QFqvQhpU53WsV) | 50% | :lock: | :one: | 09.06.2022 |
| 8.90000000.dat | [1LHjrPBeEYQv1f219VQcQ71EBpwvp3hdD5](https://www.blockchain.com/btc/address/1LHjrPBeEYQv1f219VQcQ71EBpwvp3hdD5) | 50% | :lock: | :four: | 09.06.2022 |
| 8.77089137.dat | [16Na4QHvS2rEP23igjKYfgoPqUYtZvzB5d](https://www.blockchain.com/btc/address/16Na4QHvS2rEP23igjKYfgoPqUYtZvzB5d) | 50% | :lock: | :one: | 09.06.2022 |
| 8.50023481.dat | [1KDUcZh5Z6H1of4Pwoy5ojJtkQxcQBHhnH](https://www.blockchain.com/btc/address/1KDUcZh5Z6H1of4Pwoy5ojJtkQxcQBHhnH) | 50% | :lock: | :three: | 09.06.2022 |
| 7.00000000.dat | [1MsbUGxbcW1zKvTbNq86rvteu6zm7h7Nfw](https://www.blockchain.com/btc/address/1MsbUGxbcW1zKvTbNq86rvteu6zm7h7Nfw) | 50% | :lock: | :one: | 09.06.2022 |
| 6.33718357.dat | [18fH6tk7KG998cSKXTg7v3wqLHuVu7es4i](https://www.blockchain.com/btc/address/18fH6tk7KG998cSKXTg7v3wqLHuVu7es4i) | 50% | :lock: | :one: | 09.06.2022 |
| 6.33560000.dat | [1LYdAMbjcbD8RsnThMz3HwhaGb1keyedjx](https://www.blockchain.com/btc/address/1LYdAMbjcbD8RsnThMz3HwhaGb1keyedjx) | 50% | :lock: | :one: | 09.06.2022 |
| 6.29000000.dat | [13LjzkgZQoHoUEo9CsbLJwGcc8zmnhQrRy](https://www.blockchain.com/btc/address/13LjzkgZQoHoUEo9CsbLJwGcc8zmnhQrRy) | 50% | :lock: | :one: | 09.06.2022 |
| 6.19445176.dat | [1NyECGXWqQdoNUCvNN94CoCC97AgBQcv2o](https://www.blockchain.com/btc/address/1NyECGXWqQdoNUCvNN94CoCC97AgBQcv2o) | 50% | :lock: | :one: | 09.06.2022 |
| 6.00000000.dat | [1L1iJNKBubV4KbScgKTYS85gjvBmoDpzST](https://www.blockchain.com/btc/address/1L1iJNKBubV4KbScgKTYS85gjvBmoDpzST) | 50% | :lock: | :one: | 09.06.2022 |
| 5.89290000.dat | [1MnMPxYFL6hfCRmQxm1HxyChP7CvaCDaja](https://www.blockchain.com/btc/address/1MnMPxYFL6hfCRmQxm1HxyChP7CvaCDaja) | 50% | :lock: | :one: | 09.06.2022 |
| 5.86332001.dat | [16M7J5ThnZ8TdoTzyS9nrY1c9V7gjjxmbt](https://www.blockchain.com/btc/address/16M7J5ThnZ8TdoTzyS9nrY1c9V7gjjxmbt) | 50% | :lock: | :four: | 09.06.2022 |
| 5.08877624.dat | [15zMovc6E134wsPKWXhF364DsQXkLV7wcX](https://www.blockchain.com/btc/address/15zMovc6E134wsPKWXhF364DsQXkLV7wcX) | 50% | :lock: | :one: | 09.06.2022 |
| 5.05538396.dat | [1JEsngBPtTs56qdx7UT3VzkusdmEBPAXCy](https://www.blockchain.com/btc/address/1JEsngBPtTs56qdx7UT3VzkusdmEBPAXCy) | 50% | :lock: | :one: | 11.06.2022 |
| 4.85582600.dat | [1JugtVnWfsRQB53woJCkKkLkL1HzHgXPvB](https://www.blockchain.com/btc/address/1JugtVnWfsRQB53woJCkKkLkL1HzHgXPvB) | 50% | :lock: | :one: | 09.06.2022 |
| 4.82537042.dat | [1Hrbgj881yoMYYvNvPkgGgEx6Kw8JxirLK](https://www.blockchain.com/btc/address/1Hrbgj881yoMYYvNvPkgGgEx6Kw8JxirLK) | 50% | :lock: | :one: | 09.06.2022 |
| 4.38100000.dat | [1CQyjZ8Rptd9YnZW7rX87rmni8HAPfwRgh](https://www.blockchain.com/btc/address/1CQyjZ8Rptd9YnZW7rX87rmni8HAPfwRgh) | 50% | :lock: | :three: | 09.06.2022 |
| 4.36000000.dat | [18Sb5pxmK7HNwG9dUrZhzzcAoX1n8FEUBu](https://www.blockchain.com/btc/address/18Sb5pxmK7HNwG9dUrZhzzcAoX1n8FEUBu) | 50% | :lock: | :one: | 09.06.2022 |
| 4.02219444.dat | [1L42VCpdoysXAstA9Ay4Q5V3QsK12grQ7H](https://www.blockchain.com/btc/address/1L42VCpdoysXAstA9Ay4Q5V3QsK12grQ7H) | 50% | :lock: | :one: | 09.06.2022 |
| 4.00043606.dat | [19sCR19UAdxCVPj6ATMGJV71J43X1wQoDa](https://www.blockchain.com/btc/address/19sCR19UAdxCVPj6ATMGJV71J43X1wQoDa) | 50% | :lock: | :one: | 09.06.2022 |
| 3.98999976.dat | [179ubgmB4sTRQSutRMovStFoAHxfoVnDK5](https://www.blockchain.com/btc/address/179ubgmB4sTRQSutRMovStFoAHxfoVnDK5) | 50% | :lock: | :three: | 09.06.2022 |
| 3.88501921.dat | [1DGNFJ6i4wvTAafLNux67w598bKREF5LwY](https://www.blockchain.com/btc/address/1DGNFJ6i4wvTAafLNux67w598bKREF5LwY) | 50% | :lock: | :three: | 09.06.2022 |
| 3.85090000.dat | [1GGwxGLy8PK1LUKBY71AZGessdkgdHxCd7](https://www.blockchain.com/btc/address/1GGwxGLy8PK1LUKBY71AZGessdkgdHxCd7) | 50% | :lock: | :one: | 09.06.2022 |
| 3.73979441.dat | [17KwpmAu27ycGndUU4Jwj2HvFkYEUefuJd](https://www.blockchain.com/btc/address/17KwpmAu27ycGndUU4Jwj2HvFkYEUefuJd) | 50% | :lock: | :one: | 09.06.2022 |
| 3.53383248.dat | [1NUW3z5z6cNs8Ltd2cN2BnxP92dySdcuG8](https://www.blockchain.com/btc/address/1NUW3z5z6cNs8Ltd2cN2BnxP92dySdcuG8) | 50% | :lock: | :four: | 09.06.2022 |
| 3.36894140.dat | [1BGJWEmGZhCYQEgp3pSZsBP3EYZF2c7vtS](https://www.blockchain.com/btc/address/1BGJWEmGZhCYQEgp3pSZsBP3EYZF2c7vtS) | 50% | :lock: | :one: | 09.06.2022 |
| 3.17460240.dat | [15NtoCW4eoT2L9LQRvpKtNdiHt3Lh1Sv9t](https://www.blockchain.com/btc/address/15NtoCW4eoT2L9LQRvpKtNdiHt3Lh1Sv9t) | 50% | :lock: | :one: | 09.06.2022 |
| 3.08715076.dat | [15tzMWqPk6XcW7g1AB2sLfHp8KAuzVkWBv](https://www.blockchain.com/btc/address/15tzMWqPk6XcW7g1AB2sLfHp8KAuzVkWBv) | 50% | :lock: | :one: | 09.06.2022 |
| 3.02000000.dat | [1ADuSfQpcGxQxZ22JATwdbDjxgDJHTpZ8N](https://www.blockchain.com/btc/address/1ADuSfQpcGxQxZ22JATwdbDjxgDJHTpZ8N) | 50% | :lock: | :one: | 09.06.2022 |
| 3.01244000.dat | [1L6HgRR5rJAUXb6UGK2Cu8ATLq48YRksTE](https://www.blockchain.com/btc/address/1L6HgRR5rJAUXb6UGK2Cu8ATLq48YRksTE) | 50% | :lock: | :one: | 09.06.2022 |
| 2.97000000.dat | [18cC6RJjYq5vxPAPmMA1KfszMzRr5FohLW](https://www.blockchain.com/btc/address/18cC6RJjYq5vxPAPmMA1KfszMzRr5FohLW) | 50% | :lock: | :one: | 09.06.2022 |
| 2.97000000-2.dat | [18cC6RJjYq5vxPAPmMA1KfszMzRr5FohLW](https://www.blockchain.com/btc/address/18cC6RJjYq5vxPAPmMA1KfszMzRr5FohLW) | 50% | :lock: | :one: | 09.06.2022 |
| 2.96812861.dat | [1Cr1cDL6NNzyWey66Lzt9QvCjKJXZgEs2p](https://www.blockchain.com/btc/address/1Cr1cDL6NNzyWey66Lzt9QvCjKJXZgEs2p) | 50% | :lock: | :one: | 09.06.2022 |
| 2.82717743.dat | [1PXJMEw2He6ESDJZkSzUA3eBD6XfCFrTna](https://www.blockchain.com/btc/address/1PXJMEw2He6ESDJZkSzUA3eBD6XfCFrTna) | 50% | :lock: | :one: | 09.06.2022 |
| 2.74500000.dat | [1Ea2zY7BZtLKmcT83QXscXcBudWATcSf7v](https://www.blockchain.com/btc/address/1Ea2zY7BZtLKmcT83QXscXcBudWATcSf7v) | 50% | :lock: | :one: | 09.06.2022 |
| 2.74000000.dat | [1E1nwBt5yf71VpHDhbbiWKkGPrVV5ZwhXA](https://www.blockchain.com/btc/address/1E1nwBt5yf71VpHDhbbiWKkGPrVV5ZwhXA) | 50% | :lock: | :one: | 09.06.2022 |
| 2.73000000.dat | [1K3wtJsN8pkHB61EWfFy5VKD1dk6UNpMLy](https://www.blockchain.com/btc/address/1K3wtJsN8pkHB61EWfFy5VKD1dk6UNpMLy) | 50% | :lock: | :one: | 09.06.2022 |
| 2.69500000.dat | [1AZZbKaYZns8LAGnVdPQEShMzVKxcCMCfx](https://www.blockchain.com/btc/address/1AZZbKaYZns8LAGnVdPQEShMzVKxcCMCfx) | 50% | :lock: | :one: | 09.06.2022 |
| 2.68753118.dat | [1A2FEmGPFJrUMhCXwxhMriK7KFR7ivpwQZ](https://www.blockchain.com/btc/address/1A2FEmGPFJrUMhCXwxhMriK7KFR7ivpwQZ) | 50% | :lock: | :one: | 09.06.2022 |
| 2.63049301.dat | [13EmuvWVN7phTS5o9Ru1FsYuZ43rKpGTKm](https://www.blockchain.com/btc/address/13EmuvWVN7phTS5o9Ru1FsYuZ43rKpGTKm) | 50% | :lock: | :four: | 09.06.2022 |
| 2.53794900.dat | [16ySdKvgp9bHPgjnfxUawPrmRyQBvfbuWr](https://www.blockchain.com/btc/address/16ySdKvgp9bHPgjnfxUawPrmRyQBvfbuWr) | 50% | :lock: | :one: | 09.06.2022 |
| 2.50000000.dat | [1GGtCHaMAzSex7tRaNPMG1ZC2WF5UYuZjy](https://www.blockchain.com/btc/address/1GGtCHaMAzSex7tRaNPMG1ZC2WF5UYuZjy) | 50% | :lock: | :one: | 09.06.2022 |
| 2.40000000.dat | [1AFuqjnZSveYPpaAQqH6VRssxSF9YjRxaz](https://www.blockchain.com/btc/address/1AFuqjnZSveYPpaAQqH6VRssxSF9YjRxaz) | 50% | :lock: | :one: | 09.06.2022 |
| 2.29597675.dat | [13Rb4ZMRjrkSYFLgdCJuxF7AWPngyaeC7e](https://www.blockchain.com/btc/address/13Rb4ZMRjrkSYFLgdCJuxF7AWPngyaeC7e) | 50% | :lock: | :one: | 09.06.2022 |
| 2.28883133.dat | [1FcHtQuvWrFLzqRKVgaaGHMEzL1o9bb36U](https://www.blockchain.com/btc/address/1FcHtQuvWrFLzqRKVgaaGHMEzL1o9bb36U) | 50% | :lock: | :one: | 09.06.2022 |
| 2.28384400.dat | [1CunakLPvMN4hHQzM5najUmQx2q2h8Mynv](https://www.blockchain.com/btc/address/1CunakLPvMN4hHQzM5najUmQx2q2h8Mynv) | 50% | :lock: | :one: | 11.06.2022 |
| 2.20704746.dat | [1N8L17Z7D6bBCWkSKABDf2qqJNHT1R9fv7](https://www.blockchain.com/btc/address/1N8L17Z7D6bBCWkSKABDf2qqJNHT1R9fv7) | 50% | :lock: | :one: | 09.06.2022 |
| 2.16000000.dat | [14R9c6qy3ES2YrdPhnDuncrJmqcFNdwUK8](https://www.blockchain.com/btc/address/14R9c6qy3ES2YrdPhnDuncrJmqcFNdwUK8) | 50% | :lock: | :three: | 09.06.2022 |
| 2.08763448.dat | [1JYfyscMaVHhSpqkU5mH5dFBz48etu6NPm](https://www.blockchain.com/btc/address/1JYfyscMaVHhSpqkU5mH5dFBz48etu6NPm) | 50% | :lock: | :one: | 09.06.2022 |
| 2.05917246.dat | [13A4wCqU2v5f1rMELgaJ1PV7CYD9yYPfQn](https://www.blockchain.com/btc/address/13A4wCqU2v5f1rMELgaJ1PV7CYD9yYPfQn) | 50% | :lock: | :one: | 09.06.2022 |
| 2.05423471.dat | [13TTA7LS3fvCRtUytEmW1HZwzY3kaahDqU](https://www.blockchain.com/btc/address/13TTA7LS3fvCRtUytEmW1HZwzY3kaahDqU) | 50% | :lock: | :four: | 09.06.2022 |
| 2.04866236.dat | [1QAZ3GbyK2bpuejqmoqQaveqoBDFjiY2Ds](https://www.blockchain.com/btc/address/1QAZ3GbyK2bpuejqmoqQaveqoBDFjiY2Ds) | 50% | :lock: | :one: | 09.06.2022 |
| 2.03000003.dat | [1GXR9FzCReefMfr1cWn2vFVqb7qsajTKxs](https://www.blockchain.com/btc/address/1GXR9FzCReefMfr1cWn2vFVqb7qsajTKxs) | 50% | :lock: | :one: | 09.06.2022 |
| 2.00792223.dat | [1Foen6hijntavxrwq6dC1sFKev6NYA4bbc](https://www.blockchain.com/btc/address/1Foen6hijntavxrwq6dC1sFKev6NYA4bbc) | 50% | :lock: | :three: | 09.06.2022 |
| 2.00515494.dat | [179F4iZspgdqy8Ugtw3z7wDu1kF3z1i4MG](https://www.blockchain.com/btc/address/179F4iZspgdqy8Ugtw3z7wDu1kF3z1i4MG) | 50% | :lock: | :one: | 09.06.2022 |
| 2.00000000.dat | [1NyAYbSvrx8T1YkwqnKQ6JZkTeKHcB4Les](https://www.blockchain.com/btc/address/1NyAYbSvrx8T1YkwqnKQ6JZkTeKHcB4Les) | 50% | :lock: | :one: | 09.06.2022 |
| 1.92980000.dat | [1BpehDQS3JHQmH3p8y1PrG6sycJ8S4z677](https://www.blockchain.com/btc/address/1BpehDQS3JHQmH3p8y1PrG6sycJ8S4z677) | 50% | :lock: | :one: | 09.06.2022 |
| 1.84950000.dat | [173qP26Urf7F3oJkEexfetTDjD4Y78fbjH](https://www.blockchain.com/btc/address/173qP26Urf7F3oJkEexfetTDjD4Y78fbjH) | 50% | :lock: | :one: | 09.06.2022 |
| 1.83949995.dat | [18jXjhpdiwF6R5YkPyUZMNSkxHRXEajYEq](https://www.blockchain.com/btc/address/18jXjhpdiwF6R5YkPyUZMNSkxHRXEajYEq) | 50% | :lock: | :one: | 09.06.2022 |
| 1.83913928.dat | [16pYs9RdquncSfqgVE1jARQhaLtURYnsng](https://www.blockchain.com/btc/address/16pYs9RdquncSfqgVE1jARQhaLtURYnsng) | 50% | :lock: | :one: | 09.06.2022 |
| 1.71600020.dat | [1PEbNwPneV4zs25tGEtXai38R9DX7Ly9mq](https://www.blockchain.com/btc/address/1PEbNwPneV4zs25tGEtXai38R9DX7Ly9mq) | 50% | :lock: | :one: | 09.06.2022 |
| 1.65000000.dat | [19agCPKUC8eD24W6AhrwSNwrUFtrr358vQ](https://www.blockchain.com/btc/address/19agCPKUC8eD24W6AhrwSNwrUFtrr358vQ) | 50% | :lock: | :one: | 09.06.2022 |
| 1.56079001.dat | [1CyiqmkPFb7SysXhhTdtd8ajpz58t5xFRY](https://www.blockchain.com/btc/address/1CyiqmkPFb7SysXhhTdtd8ajpz58t5xFRY) | 50% | :lock: | :three: | 09.06.2022 |
| 1.44138096.dat | [17YbJhRweKx2tVqepkvMYKvP9zxLfXLKoz](https://www.blockchain.com/btc/address/17YbJhRweKx2tVqepkvMYKvP9zxLfXLKoz) | 50% | :lock: | :one: | 09.06.2022 |
| 1.44124101.dat | [1Lc6RJEB99cXMRBnkuTZqqojv6pRjikCkA](https://www.blockchain.com/btc/address/1Lc6RJEB99cXMRBnkuTZqqojv6pRjikCkA) | 50% | :lock: | :one: | 09.06.2022 |
| 1.39498354.dat | [1CcnHNGyxM6FCfjMrV5dwBW1mngGnUkFMF](https://www.blockchain.com/btc/address/1CcnHNGyxM6FCfjMrV5dwBW1mngGnUkFMF) | 50% | :lock: | :one: | 09.06.2022 |
| 1.09479390.dat | [1AS8nsUcQYvJQJDrxi9rpjSHa5n9hVLLno](https://www.blockchain.com/btc/address/1AS8nsUcQYvJQJDrxi9rpjSHa5n9hVLLno) | 50% | :lock: | :one: | 09.06.2022 |
| 1.08795916.dat | [1F654t1HxrZtg7uhcXyZeFvRsyB8HCnBXJ](https://www.blockchain.com/btc/address/1F654t1HxrZtg7uhcXyZeFvRsyB8HCnBXJ) | 50% | :lock: | :three: | 09.06.2022 |
| 1.00103254.dat | [1AxhH9CKkP1WBoT9bF1jFQo2nEdPDooP4i](https://www.blockchain.com/btc/address/1AxhH9CKkP1WBoT9bF1jFQo2nEdPDooP4i) | 50% | :lock: | :one: | 09.06.2022 |
| 0.92387567.dat | [19wCFh3wAqqWE9SNJu6QyBmCVX68zVGLH5](https://www.blockchain.com/btc/address/19wCFh3wAqqWE9SNJu6QyBmCVX68zVGLH5) | 50% | :lock: | :one: | 09.06.2022 |
| 0.53970361.dat | [1MJ5ebhcgZczc5qvdJM3h5SNYgUjDxjWeD](https://www.blockchain.com/btc/address/1MJ5ebhcgZczc5qvdJM3h5SNYgUjDxjWeD) | 50% | :lock: | :one: | 09.06.2022 |
| 0.39370194.dat | [1JQLXZdb19UcW2z6m3FzNUbVRKTU8ke7MV](https://www.blockchain.com/btc/address/1JQLXZdb19UcW2z6m3FzNUbVRKTU8ke7MV) | 50% | :lock: | :one: | 09.06.2022 |
| 0.36688060.dat | [1AaB2jXukNRcY88ichcuSvwvgKkNdWaNPC](https://www.blockchain.com/btc/address/1AaB2jXukNRcY88ichcuSvwvgKkNdWaNPC) | 50% | :lock: | :one: | 09.06.2022 |
| 0.29957903.dat | [1Fd4kGGuBwxH2QZe6cTS5GATXQeFBMmxKJ](https://www.blockchain.com/btc/address/1Fd4kGGuBwxH2QZe6cTS5GATXQeFBMmxKJ) | 50% | :lock: | :four: | 09.06.2022 |
| 0.21966138.dat | [1KVBdT8ypyywuisonw6k69UUynARJ366JW](https://www.blockchain.com/btc/address/1KVBdT8ypyywuisonw6k69UUynARJ366JW) | 50% | :lock: | :one: | 09.06.2022 |
| 0.10000000.dat | [1DH3GZaGLbgFvVPP9NzZDZXQweKhU2BHeG](https://www.blockchain.com/btc/address/1DH3GZaGLbgFvVPP9NzZDZXQweKhU2BHeG) | 50% | :lock: | :one: | 09.06.2022 |
| 0.07394004.dat | [12vdxXV3m5xRTi6vAAwMkQQkVL5rh9LESE](https://www.blockchain.com/btc/address/12vdxXV3m5xRTi6vAAwMkQQkVL5rh9LESE) | 50% | :lock: | :three: | 09.06.2022 |
| 0.06271293.dat | [15zrzE1psJJGjXyPiLkLTbiqwcjvE4hu7d](https://www.blockchain.com/btc/address/15zrzE1psJJGjXyPiLkLTbiqwcjvE4hu7d) | 50% | :lock: | :one: | 09.06.2022 |
| 0.05847536.dat | [19bdmxEtNgt1ogTWCYpGW2Qpn4qBmfUnGk](https://www.blockchain.com/btc/address/19bdmxEtNgt1ogTWCYpGW2Qpn4qBmfUnGk) | 50% | :lock: | :one: | 09.06.2022 |
| 0.04157575.dat | [1EjMaPCv4EyEVXWtWyPSD7HjAb4nZ9iADK](https://www.blockchain.com/btc/address/1EjMaPCv4EyEVXWtWyPSD7HjAb4nZ9iADK) | 50% | :lock: | :one: | 09.06.2022 |
| 0.02994543.dat | [1JsUStZoy9aHqFkH3Gqpz4RQFCFqyhk5W7](https://www.blockchain.com/btc/address/1JsUStZoy9aHqFkH3Gqpz4RQFCFqyhk5W7) | 50% | :lock: | :one: | 09.06.2022 |
| 0.01786378.dat | [12d31NMtE18xgdRLdhDgDs7BSSXxsZaH8r](https://www.blockchain.com/btc/address/12d31NMtE18xgdRLdhDgDs7BSSXxsZaH8r) | 50% | :lock: | :three: | 09.06.2022 |
| 0.01649536.dat | [16euRht9j5pysEQ8GSyqvWQWSVL9zmBvf6](https://www.blockchain.com/btc/address/16euRht9j5pysEQ8GSyqvWQWSVL9zmBvf6) | 50% | :lock: | :one: | 09.06.2022 |
| 0.01630413.dat | [1CxKn8H3tbo7s7qzExVD3eFs94nceNiiRV](https://www.blockchain.com/btc/address/1CxKn8H3tbo7s7qzExVD3eFs94nceNiiRV) | 50% | :lock: | :one: | 09.06.2022 |
| 0.01212207.dat | [1HQ3Go3ggs8pFnXuHVHRytPCq5fGG8Hbhx](https://www.blockchain.com/btc/address/1HQ3Go3ggs8pFnXuHVHRytPCq5fGG8Hbhx) | 50% | :lock: | :one: | 09.06.2022 |
| 0.01000000.dat | [18MW7RLHthpRDmzcfDjFSaTamxNSSkMs67](https://www.blockchain.com/btc/address/18MW7RLHthpRDmzcfDjFSaTamxNSSkMs67) | 50% | :lock: | :one: | 09.06.2022 |
| 0.00900000.dat | [16PCQnhRNZoD2jGuCNvfJS3aCZeELsX34A](https://www.blockchain.com/btc/address/16PCQnhRNZoD2jGuCNvfJS3aCZeELsX34A) | 50% | :lock: | :one: | 09.06.2022 |
| 0.00122539.dat | [15KeSdnNDVrCQ62TGFRNEx3xedKwXMpvn5](https://www.blockchain.com/btc/address/15KeSdnNDVrCQ62TGFRNEx3xedKwXMpvn5) | 50% | :lock: | :one: | 09.06.2022 |
| 0.00044000.dat | [1745e6GxkbEjsL28b9qpSHQKGBpWxFtQsD](https://www.blockchain.com/btc/address/1745e6GxkbEjsL28b9qpSHQKGBpWxFtQsD) | 50% | :lock: | :four: | 09.06.2022 |
| 0.00000580.dat | [17bqkPW21QhRUBcUQiy3C99ZC6L52Utu1b](https://www.blockchain.com/btc/address/17bqkPW21QhRUBcUQiy3C99ZC6L52Utu1b) | 50% | :lock: | :three: | 09.06.2022 |

#### Trust them or not, it's up to you
```
1AamCcS7oXPZYvYw7dwcZxjxJkPSxZ94vm - EN user, 9 characters long.</br>
1An4jHFsSz31TjW49vsZtCt2SXKV7oHRWb - The length of the password from the source is 8-10 characters, the password was generated with the entire set of special characters.</br>
1BpehDQS3JHQmH3p8y1PrG6sycJ8S4z677 - Password 13 characters layout unknown.</br>
1FJBeYLRArReqVTiqwYTEc9hAfypGx8MyN - Password 11 characters without capital letters.</br>
1GYLfNfMesF3YrwVU94P5wtcJjhAx9DLYy - The password contains three characters 8 ~ , the length of the password is 10-12 characters.</br>
1P2kKdepEAJQwVHoaodfQKD6jSJC86z1Yw - Nothing is known about the password.</br>
1PYeoCUYbq6zsh7BcyRgeAQdkFGnhCY95T - Password is twisted up to 7 characters including Turkish. Nothing is known about the password.</br>
16ySdKvgp9bHPgjnfxUawPrmRyQBvfbuWr - Russian user claims that his brother's wallet is unknown in which direction to dig.</br>
18jXjhpdiwF6R5YkPyUZMNSkxHRXEajYEq - The password consists of the English layout including 2 characters (-) the length is unknown.</br>
19sCR19UAdxCVPj6ATMGJV71J43X1wQoDa - The password is 15 characters long at the end of the password is the year 1985.</br>
17KwpmAu27ycGndUU4Jwj2HvFkYEUefuJd - English layout password 12 characters.
1AZZbKaYZns8LAGnVdPQEShMzVKxcCMCfx - the password has uppercase English letters special characters. The length of the password is unknown.
1MsbUGxbcW1zKvTbNq86rvteu6zm7h7Nfw - the password was lost, everything that is known about the length was invented by the user - more than 10 characters.
13Rb4ZMRjrkSYFLgdCJuxF7AWPngyaeC7e - Password 9-10 characters - from where and whose information is unknown.
15npoeYGso1qyFAo7Wzw35s4fXMDh5ryrj - password 13 characters
18HKjVPJwfDg7TDSpoVh2KBiTQny6hymMX - password 9 characters, there is a space.
1LJxQSJ1uf2VHq4RDZgHQgEwn8JRAr6btq - password 12 characters English (
1NuPEefRU2AZ319x45fY5wBHBV2Z72PY98 - password 17 characters, English.
1DphS33aWDZBWNEh3rPJFfD6GFP1mmgerU - password generated 14 characters.
1KVBdT8ypyywuisonw6k69UUynARJ366JW - nothing is known about the password and owner.
1DDYt8kJE1JBa2kQN1R921weJGbCnWcgG4 - password 11 characters formed there are special characters.
1BGJWEmGZhCYQEgp3pSZsBP3EYZF2c7vtS - password 12 characters
18MW7RLHthpRDmzcfDjFSaTamxNSSkMs67 - Forgot password
1Aw6miK9me2AijQ76Q32NkPa1B7buWqWPg - according to the information there is nothing
1CxKn8H3tbo7s7qzExVD3eFs94nceNiiRV - password of 10 characters.
1HuTxwnZMyaNRTsHJ2Xg83Z7mt75dtdwC3 - password of 10 characters. there is a dot in the password.
16Na4QHvS2rEP23igjKYfgoPqUYtZvzB5d - password 15 characters in front of the name GEORG.
16PCQnhRNZoD2jGuCNvfJS3aCZeELsX34A - password is 13 characters, there is a space and number 9 in the password, nothing else is known about the password.
1AHgGcw8LjzhsRKtKxjvyRSUSAnkcAEMjX - a 9 character password has been generated.
15KeSdnNDVrCQ62TGFRNEx3xedKwXMpvn5 - forgot password
15LhbzoCjr9icNTsabMVBKCgTZYqPHgcaf - Password 17 characters, generated 100% honest information.
1LmdsdywkMNqgXg7x7q88NT2WeXXf52co3 - Password is 14 characters German keyboard layout.
15zrzE1psJJGjXyPiLkLTbiqwcjvE4hu7d - From the owner's mouth, the password consists of 13 characters.
1JsUStZoy9aHqFkH3Gqpz4RQFCFqyhk5W7 - 11 characters, it is not known what is in the password, it may be false. (according to my suspicions)
13q3UMbUdqak1xX385aZc3MmtdMtNfsnSU - the file was distributed by 2 persons, according to the owner, the password was 8 characters, the password was not found for 8 characters all extent including both English and Russian with special characters and space.
1DCqdVEh91bVzEShe6iU5iuNrd1LbsWvgf - I forgot my password, but it was easy to remember in my head, I can't say the length for sure, I don't even know what characters are in the password.
1A2FEmGPFJrUMhCXwxhMriK7KFR7ivpwQZ - Password 12 characters, layout unknown.
1Cr1cDL6NNzyWey66Lzt9QvCjKJXZgEs2p - Password 17 characters from which 5 characters hash (#)
1CunakLPvMN4hHQzM5najUmQx2q2h8Mynv - Password 11 characters. The layout is unknown.
1K3wtJsN8pkHB61EWfFy5VKD1dk6UNpMLy - Password 15 characters. The layout is unknown.
1K9k7LP1e3GQ6fF8dimzKp8oGWiwkBdtUu - Password 13 characters, there is a space in the password, Russian layout.
1L6HgRR5rJAUXb6UGK2Cu8ATLq48YRksTE - Unknown password, unknown whose file.
1LhKQqkjzxxzve61HYytPYJ7oVMh88aV4T - Password 14 characters, English user.
15tzMWqPk6XcW7g1AB2sLfHp8KAuzVkWBv - Password 10 characters, generated.
18Sb5pxmK7HNwG9dUrZhzzcAoX1n8FEUBu - The password is more than 10 characters, the exact length is unknown.
1B5FuKQgmPg4SJsCjFU3svrFPpZpQZMU1d - 8 characters long. The layout is unknown.
1EjMaPCv4EyEVXWtWyPSD7HjAb4nZ9iADK - 11 characters. The layout is unknown.
1EREjjsLgB5JJQhN89gQR9PvH89yWJ4kuV - The password consists of numbers and small letters of the English layout. The length is unknown.
1F3yxoWp5TdpVzbziVJ2VnvhpaXJma3qnF - 13 characters. The layout is unknown.
1GGtCHaMAzSex7tRaNPMG1ZC2WF5UYuZjy - No password information.
1H9WV22GeCQuTGQbwTEQfGZhvTVhNsscNr - Password generated Unknown length, Unknown layout.
1HBXJBXWYM1jZd8p1ff2a4uhJxvtgoXiYU - The password has 999 at the end. The length is unknown.
1Lc6RJEB99cXMRBnkuTZqqojv6pRjikCkA - Lost password, longer than 10 characters. The layout is unknown.
1Lefr9kXBybeW4SG1KtpysnnKKftnDYTvP - 14 character password.
1NFp8YqgBjSRFdgWt7ynmojG8gpQDjVDpJ - Longer than 15 characters, password from address, strong.
1PXJMEw2He6ESDJZkSzUA3eBD6XfCFrTna - 8 characters long, mixed languages, unknown password.
13KKv3ywwJ5WYovLgiCAaqpCVuMDEF6oxo - Password 9 characters generated, strong.
14jt9AzqeM1TX3oQCGWkQbtfeUYih3o56W - A password with 10 characters has been generated. The layout is unknown.
15NtoCW4eoT2L9LQRvpKtNdiHt3Lh1Sv9t - No password information.
16euRht9j5pysEQ8GSyqvWQWSVL9zmBvf6 - Lost password, length unknown, capital letter F present in password
16Wi4S2Dn9sK2VVtP5EgA3UP1zEry6oY8X - Password with numbers and capital letters of the English layout. The length is unknown.
18H3tXBX9fC2AguKV2m34YKHYugN1Y4XkA - 10-12 characters long, the password contains the name nikolay.
18snvPxfy9SGZUNe9i7kUJced3PEdVWodm - 11 characters long. The layout is unknown.
19zrj2vTBBSX5e4onaHWGaCTe5mFskwAsD - Lost password, was generated, more than 10 characters.
179F4iZspgdqy8Ugtw3z7wDu1kF3z1i4MG - No password information.
1AS8nsUcQYvJQJDrxi9rpjSHa5n9hVLLno - password 15(+) characters, lost, I don't recommend using this wallet.
1QAZ3GbyK2bpuejqmoqQaveqoBDFjiY2Ds - Japanese - length unknown.
1AaB2jXukNRcY88ichcuSvwvgKkNdWaNPC - Korean 6 characters.
1AFuqjnZSveYPpaAQqH6VRssxSF9YjRxaz - Password created by user, length unknown, Caps Lock was enabled.
1GXR9FzCReefMfr1cWn2vFVqb7qsajTKxs - Little is known about the wallet and it's not a fact that it's 9 characters long.
1L1iJNKBubV4KbScgKTYS85gjvBmoDpzST - Password 11 characters, nothing more is unknown.
1L42VCpdoysXAstA9Ay4Q5V3QsK12grQ7H - 7-9 characters long, English user.
1NyECGXWqQdoNUCvNN94CoCC97AgBQcv2o - A password of 5 characters has been set, (passed 4,5,6,7,8) whoever has the power can try up to 10, maybe lucky.
18cC6RJjYq5vxPAPmMA1KfszMzRr5FohLW - Russian user, does not remember the password. Bought for 30$
18EGA8nGHjA998Qc17je6K8T6UUDHxeoCH - According to the owner, the password was in small letters, about 8-9 characters.
18fH6tk7KG998cSKXTg7v3wqLHuVu7es4i - 8 characters, it is known that there is a space in the password and Shift was also used.
1F11GQNQKTEme6L74c5dVTTMkD7ME2jiqP - Password 12 characters, we only know that there is a space in the password.
1MJ5ebhcgZczc5qvdJM3h5SNYgUjDxjWeD - The password is 8 characters long, the password was created by the user. EN layout.
173qP26Urf7F3oJkEexfetTDjD4Y78fbjH - English user, can't remember password. From words did not use capital letters for the password.
14tZU9KyHXwkGXkVUKehkMfaEZ8ad7jwNc - The Russian user changed the password after the wallet was restored, from the words the password was from English letters mixed with large and small 9 characters.
1BvNsod2wBpjoJmYmbnhk1j9FLLWz7HzZE - the password starts with the word HEX, the length is unknown.
1E1nwBt5yf71VpHDhbbiWKkGPrVV5ZwhXA - Password generated 9 characters, EN layout.
1CcnHNGyxM6FCfjMrV5dwBW1mngGnUkFMF - Password forgotten. Russian user.
15zMovc6E134wsPKWXhF364DsQXkLV7wcX - Nothing is known about the password and owner.
16pYs9RdquncSfqgVE1jARQhaLtURYnsng - Password 1A1A0199005F5E07 stopped working after some manipulations with the file.
1MnMPxYFL6hfCRmQxm1HxyChP7CvaCDaja - Password 14 characters, 4 characters year of birth 1989.
1NyAYbSvrx8T1YkwqnKQ6JZkTeKHcB4Les - Lost password, length unknown.
17YbJhRweKx2tVqepkvMYKvP9zxLfXLKoz - Length of 8 characters in the password flash was used unknown with them - \ / |
1AxhH9CKkP1WBoT9bF1jFQo2nEdPDooP4i - A password has been generated, more than 10 characters it is known that the first capital letter is D
19agCPKUC8eD24W6AhrwSNwrUFtrr358vQ - The password consists of sick letters of the English layout.
1ADuSfQpcGxQxZ22JATwdbDjxgDJHTpZ8N - Password length 11 characters, English layout.
1LYdAMbjcbD8RsnThMz3HwhaGb1keyedjx - Restored file.
13vq3LDCBpwbyxSenJDpHWt3xCXgbtzp9V - Russian user, password with 20 characters under the capslock of the English layout.
16vMxeMHJDbMoDu2s1ozDQAmzY3bPmdLLi - password ETH transaction number for 2016 is all that is known about the wallet.
17w8w8ZHdqkSYFkhAMfHJaEqCHgHm9egKv - Generated password, English layout (small), length more than 10 characters
18h7ETAzcqRCGNXTstWSavrvhy5S5YKsQF - A British user claimed to have 2013 in front of the password, followed by his former car number. 2013GF54KHG
19Hj5Pzi4hCj12porw97i183XYTrScbtXS - The password consists of 10 special characters.
19tLSCZWhX5YBVy6uX2kLheNjdUb9RBojS - 9 characters With capslock enabled, character set unknown.
1AYyMBbxXv9E29qJoTpbd6ocje81ZAJQsF - 8 characters, it is known that there are special characters in the password, the password was generated by some software on the PC.
1BSmyTdYpsHA5JhLS9azGmVADuJRiLWE5Z - password - name (dima) and 8 en characters (unknown), dima00000000+/-1 symbol.
1DGNFJ6i4wvTAafLNux67w598bKREF5LwY - B53bd8c350f7C17bc00976B the password that I set. I checked English and Russian for caps - it didn't open.
1E4ad5bA8HgbqxsPYpmDtVRNBRF2XfqTns - Chinese user. the password length is 12 characters, what was used in the password is unknown, the information was received not from the owner, but from the 2nd person and may not be accurate.
1EQjwXjyom9T35764huyriFEredLGmneVC - Russian password 10 characters (small).
1Gj2KiTy9SFtuFSJECmpePseYchhkU3gXQ - An English-speaking user set a password from Wikipedia, a link to the page https://en.wikipedia.org/wiki/Crypto from one of the sections, he set a completed speech to the password, something like The war in the Pacific was similarly helped by 'Magic' intelligence. The password starts with a capital letter and ends with a slash.
1JHqAnwohyhXgvwNnzEMeMwejsf6vHZhgp - The Russian user has generated a password from large small English and numbers, the length of the password is unknown.
1KTvsW5tg5gkJf9fyT2xsvjkv7dzuZNTpW - The English user in the password has a nickname with the year, the nickname does not remember but the year is 1989.
1LHjrPBeEYQv1f219VQcQ71EBpwvp3hdD5 - The length of the password is 10 characters from which only three R+2 are known, in which location is unknown.
1LwQU2kqdH6dLSsizstNxrhqk7XhCMLMF3 - The password contains 15 characters, English, the password format is formed, which is unknown in the password.
1MB28otoAQFpP9ywiA8CbYVSKHpSTBH1z6 - Password of 8 characters, small EN, numbers, special characters.
1N8L17Z7D6bBCWkSKABDf2qqJNHT1R9fv7 - The Chinese miner set a password with 7 characters, the layout is unknown.
1NKmf6GszBQ6wo349LUT4Je1csNyDDpb5Y - 9 characters, there is a space, there are numbers, there is a special character $ layout En
1NibfhHfgA857dtG6pB25Y5hDcxpDo2J47 - A person is a gamer, as well as a participant in the German rally, the length of the password is the first CMR characters, the remaining 6 are unknown, you need to storm in German, it only looks like symbols in English, but for some reason someone does not take into account that the owner is not English but German.
1NuNHWG4Ujs9wjH9wciVEoJCsgXmn6PfX9 - The Russian password consists of numbers and letters, the length is unknown, all possible combinations of up to 9 characters have been tried.
1NyEeyXu8ydNw67e3ZTUmkwQJ8QNd1o3cF - Руский пользователь, поставил фразу с журнала про авто ВАЗ 2101 что за фраза и какой она длинны он непомнит.
1PbHeg1WDosvuhApxbfQg3iFDQ2WW7Mttf - English user, password no more than 10 characters who knew by heart. The password contains a space with a date. which means there are numbers and a space in it 100%
1QFDAGXRkhNYfx2mHEu81QH8dAj4go4A8d - A Chinese user, it is known that the password begins with qin (цынь) - followed by a password with 10 characters that he lost.

```

## Heshes table




## Frequently asked Questions
**Are your wallets real?**</br>

99% - YES</br>
Wallets were maximally checked for validity.</br>
Coins were sent to some dubious wallets for verification.</br>
There is no way to verify wallet.dat is 100%</br>
This can only be done if the correct password is entered.<hr>

**How do you have so many wallets?**</br>

Jacks were presented to me by various hunters for 25% of the amount of the find.</br>
Hunters received wallet.dat by exchanging with other hunters.<hr>

**If I find. What are the guarantees of paying me 50% ?**</br>

If you find the hash password.</br>
Write to me in telegram ```phrutis```</br>
After agreeing, and receiving your BTC address from you.</br>
Sending coins to 3 addresses will be prepared.</br>
Your address is 50% 1......?</br>
Partner address 25% (btc address from table)</br>
My address is 25% bc1qh2mvnf5fujg93mwl8pe688yucaw9sflmwsukz9</br>

A password will be required to confirm the transfer.</br>
I give you the id of a [**Anydesk**](https://anydesk.com) (Windows remote desktop) running bitcoin core.</br>
You connect, you see the active bitcoin core what and where it is sent. </br>
Check your address, enter your password and click send transfer.</br>
So there will be a guarantee and security for all participants.</br>
The characters are hidden in the input window.</br>
An example of a screenshot of entering a password</br>
![pass](https://user-images.githubusercontent.com/82582647/171959020-8192f5ad-6d3c-4295-af77-8fe348769853.png)
<hr>

**I have an old wallet.dat (not from a table) want 25%**</br>

You can contact me in telegram ```phrutis```</br>
Provide me with the old wallet.dat</br>
After verification, it will be added to the table with your btc address.</br>
If hunters find password you will get 25%<hr>

**I have a wallet.dat with the same hex, there is a different amount, it's empty, it's a fake?**</br>

You may have an older version of wallet.dat</br>
There is a newer one in the challenge.</br>
In a later version, the user could add a new address and receive coins on it.</br>
The old version of wallet.dat does not have this address.</br>
Or vice versa.<hr>


**Sell me all your wallets**</br>

I don't sell or buy wallet.dat</br>
And I do not advise you to buy.<hr>

