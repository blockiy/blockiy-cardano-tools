# Service Scope

This document defines the standard scope of Blockiy's Professional Cardano Stake Pool Setup service.

The final technical design may vary according to the operator's hosting provider, selected server resources, Cardano network requirements, and agreed service scope.

## Included in the Service

### Infrastructure Preparation

* Review the intended server environment before deployment
* Prepare the operating system for Cardano node operation
* Apply essential server-hardening and firewall configuration
* Configure appropriate system services and automatic restart behaviour
* Configure practical resource and operational settings for the deployed environment

### Cardano Node Deployment

* Install the required Cardano node software
* Configure and synchronize the node with the Cardano network
* Configure a block producer and relay-node architecture
* Configure network connectivity, relay communication, and P2P settings where applicable
* Verify core node operation, synchronization, peer connectivity, and service recovery behaviour

### Pool Operational Configuration

* Guide the operator through the required pool-key workflow
* Support the operator during pool registration preparation
* Assist with pool metadata and public operational configuration
* Provide KES operational guidance and expiry-management practices
* Review the final configuration before handover

### Reliability and Recovery Planning

* Configure safe service-management practices
* Provide backup planning for non-sensitive configurations and operational data
* Provide recovery guidance for common infrastructure issues
* Prepare the infrastructure for future Mithril integration where appropriate
* Complete basic health checks at deployment handover

### Included Support

The service includes one year of reasonable technical support for the infrastructure deployed by Blockiy.

Support may include:

* Guidance for routine infrastructure questions
* Assistance diagnosing node, relay, synchronization, or service-management issues
* Guidance for planned maintenance
* Practical assistance with supported configuration issues
* Recommendations for necessary security or software updates

## Deliverables

After successful handover, the operator receives:

* A deployed Cardano stake pool infrastructure
* Block producer and relay-node operational configuration
* A secure access and recovery handover checklist
* Non-sensitive configuration and service-management information
* Basic operating guidance for the deployed environment
* The included one-year technical support period

## Not Included

The following are outside the standard service scope unless agreed separately in writing:

* Cloud hosting, server rental, domain, or external-service fees
* Pool pledge, ADA deposits, transaction fees, or other blockchain costs
* Delegator acquisition, marketing, or pool promotion
* Guaranteed blocks, rewards, pool ranking, uptime, or delegation
* Custody of ADA, wallets, private keys, or recovery phrases
* Management of the operator's spending or payment keys
* Custom website, dashboard, application, or plugin development
* Recovery of lost private keys, seed phrases, passwords, or wallet access
* Support for infrastructure changed by third parties without review
* Major future infrastructure upgrades beyond the agreed support scope

## Operator Responsibilities

The operator is responsible for:

* Owning and paying for all required hosting and third-party services
* Maintaining ownership of server accounts, pool keys, wallets, and recovery information
* Performing sensitive key-generation and signing actions under their own control
* Keeping operating systems, hosting accounts, and contact details secure
* Reviewing and approving pool registration details before submission
* Following the operational and security guidance provided at handover

## Scope Changes

Requests outside this standard scope may require a separate quote, timeline, or service agreement.

Blockiy will communicate any material scope change before beginning additional work.
