### NIPs

Nebulas Improvement Proposals (NIPs) describe standards for the Nebulas platform, including core protocol specifications, client APIs, and contract standards.

### Contributing

Then clone the repository and add your NIP to it. There is a template NIP [here](https://github.com/nebulasio/NIPs/blob/master/NipTemplate.md). Then submit a Pull Request to Nebulas's NIPs repository.

### NIP status terms

* <b>Draft</b> - an NIP that is open for consideration.
* <b>Accepted</b> - an NIP that is planned for immediate adoption, i.e. expected to be included in the next hard fork (for Core/Consensus layer NIPs).
* <b>Final</b> - an NIP that has been adopted in a previous hard fork (for Core/Consensus layer NIPs).
* <b>Deferred</b> - an NIP that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.

### NIP Types
NIPs are separated into a number of types, and each has its own list of NIPs.

##### Standard Track
Describes any change that affects most or all Nebulas implementations, such as a change to the the network protocol, a change in block or transaction validity rules, proposed application standards/conventions, or any change or addition that affects the interoperability of applications using Nebulas. Furthermore Standard NIPs can be broken down into the following categories.

##### Core
Improvements requiring a consensus fork, as well as changes that are not necessarily consensus critical but may be relevant to “core dev” discussions (for example, the miner/node strategy changes).

##### Networking
Includes improvements around network protocol, as well as proposed improvements to network protocol specifications of whisper and swarm.

##### Interface
Includes improvements around client API/RPC specifications and standards.

##### NRC
Application-level standards and conventions, including contract standards such as token standards (NRC20)

##### Informational
Describes a Nebulas design issue, or provides general guidelines or information to the Nebulas community, but does not propose a new feature. Informational NIPs do not necessarily represent Nebulas community consensus or a recommendation, so users and implementers are free to ignore Informational NIPs or follow their advice.

##### Meta
Describes a process surrounding Nebulas or proposes a change to (or an event in) a process. Process NIPs are like Standards Track NIPs but apply to areas other than the Nebulas protocol itself. They may propose an implementation, but not to Nebulas's codebase; they often require community consensus; unlike Informational NIPs, they are more than recommendations, and users are typically not free to ignore them. Examples include procedures, guidelines, changes to the decision-making process, and changes to the tools or environment used in Nebulas development. Any meta-NIP is also considered a Process NIP.