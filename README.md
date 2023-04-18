## IPSG - Case studies

IPSG (Invariant Proof Score Generator) can automatically generate proof scores for formal invariant property verification. 
For the tool installation, please see the repository: https://github.com/duongtd23/IPSG-tool.
This repository contains ten case studies, demonstrating the efficiency and the practicability of IPSG:

- `A-Anderson`: A revised and abstract version of the Anderson mutual exclusion protocol.
- `Cloud`: A simplified cloud synchronization protocol .
- `IFF` (Identify Friend or Foe): an authentication protocol that verifies whether a principal is a member of a group.
- `MCS`: a mutual exclusion protocol invented by Mellor-Crummey and Scott. See README in that folder for: 

    1. the experimental results of MCS when the technique "case splitting is used first before reduction" is used with different thresholds, and
    2. some other invariant property/lemma candidates when the technique Lemma Weakening is not used.
    
- `NSLPK` (Needham-Schroeder-Lowe Public Key): a modified version made by Lowe of the classical authentication Needham-Schroeder Public Key (NSPK) protocol.
- `Qlock`: a mutual exclusion protocol based on queue.
- `SDS`: a simplified version of the classical key distribution protocol proposed by Denning and Sacco.
- `SKP` (Suzuki-Kasami): a distributed mutual exclusion protocol invented by Ichiro Suzuki and Tadao Kasami.
- `TAS` (Test and Set): a mutual exclusion protocol that uses the atomic instruction test&set.
- `TLS` (Transport Layer Security): the TLS 1.2 Handshake Protocol.