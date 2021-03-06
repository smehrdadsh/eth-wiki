# Byzantium Hard Fork changes

## What changes are included in the Byzantium hard fork?

The following upgrades are included:

-   Addition of ‘REVERT’ opcode, which permits error handling without consuming all gas (<a href="https://github.com/ethereum/EIPs/pull/206">EIP 140</a>)
-   Transaction receipts now include a status field to indicate success or failure <a href="https://github.com/ethereum/EIPs/pull/658">EIP 658</a>)
-   Elliptic curve addition and scalar multiplication on alt_bn128 (<a href="https://github.com/ethereum/EIPs/pull/213">EIP 196</a>) and pairing checks (<a href="https://github.com/ethereum/EIPs/pull/212">EIP 197</a>), permitting ZK-Snarks and other cryptographic mathemagic™
-   Support for big integer modular exponentiation (<a href="https://github.com/ethereum/EIPs/pull/198">EIP 198</a>), enabling RSA signature verification and other cryptographic applications
-   Support for variable length return values (<a href="https://github.com/ethereum/EIPs/pull/211">EIP 211</a>)
-   Addition of the ‘STATICCALL’ opcode, permitting non-state-changing calls to other contracts (<a href="https://github.com/ethereum/EIPs/pull/214">EIP 214</a>)
-   Changes to the difficulty adjustment formula to take uncles into account (<a href="https://github.com/ethereum/EIPs/issues/100">EIP 100</a>)
-   Delay of the ice age / difficulty bomb by 1 year, and reduction of block reward from 5 to 3 ether (<a href="https://github.com/ethereum/EIPs/pull/669">EIP 649</a>)

Source: verbatim extract from [this Ethereum blog post](https://web.archive.org/web/20180104055521/https://blog.ethereum.org/2017/10/12/byzantium-hf-announcement/).
