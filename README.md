# Verifiable Client Diversity

Client diversity is considered crucial by the Ethereum community. However, client diversity is out-of-protocol.
We consider this a shortcoming of the protocol, and we point to two potential improvements:

We propose to enforce client diversity at the protocol level. Specifically, with higher economical incentives to operators which use minority clients.
This will fundamentally enhance network integrity and reliability with verifiable client diversity, beyond advocacy.

We propose integrating interactive fraud proofs into the Ethereum network such that verified minority clients are rewarded with financial incentives.
These minority client proofs would require nodes to provide cryptographic evidence of using specific client implementations, verified by other participants in the network. 

Paper: [Proving and Rewarding Client Diversity to Strengthen Resilience of Blockchain Networks](http://arxiv.org/pdf/2411.18401) (Javier Ron, Zheyuan He and Martin Monperrus), ACM Distributed Ledger Technologies: Research and Practice, 2025.

```bibtex
@article{vcd,
 title = {Proving and Rewarding Client Diversity to Strengthen Resilience of Blockchain Networks},
 journal = {ACM Distributed Ledger Technologies: Research and Practice},
 year = {2025},
 doi = {10.1145/3773288},
 author = {Javier Ron and Zheyuan He and Martin Monperrus},
 url = {http://oadoi.org/10.1145/3773288},
}
```

 
Team: Javier Ron, Zheyuan He, Martin Monperrus (KTH Royal Institute of Technology, Stockholm, Sweden) Benoit Baudry (Université de Montréal)



## Resources

- Modified Lighthouse client
  - zkVM [https://github.com/ASSERT-KTH/lighthouse/tree/risc0-bls]
  - TEE [https://github.com/ASSERT-KTH/lighthouse/tree/tee-bls]
- Testnet with validation contracts
  - Modified Kurtosis supporting docker -v mounts [https://github.com/ASSERT-KTH/kurtosis]
  - Kurtosis YAML [https://github.com/ASSERT-KTH/lighthouse/blob/tee-bls/network-params.yaml]
- SGX attestation
  - [https://github.com/javierron/sgx-scaffold]
