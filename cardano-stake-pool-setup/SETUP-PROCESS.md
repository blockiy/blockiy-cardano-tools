# Setup Process

Blockiy follows a clear setup process designed to keep the pool operator in control of all private keys, wallets, and infrastructure ownership.

## 1. Service Enquiry and Scope Confirmation

The operator contacts Blockiy to discuss the planned stake pool and confirm the service scope.

Before deployment begins, Blockiy confirms:

* The intended Cardano network
* The required pool architecture
* Hosting and server requirements
* The agreed deliverables
* The service price and any third-party costs
* The secure communication method for the project

## 2. Operator Prepares the Infrastructure

The operator creates or purchases the required hosting environment in their own name.

The operator remains the owner of:

* Hosting-provider accounts
* Server accounts
* Billing information
* Domain names
* Wallets and pool keys
* Pool rewards

Blockiy can provide guidance on the required infrastructure before the operator orders a server.

## 3. Secure Temporary Server Access

If remote deployment access is required, the operator creates a dedicated temporary server account for Blockiy.

The preferred method is:

* SSH public-key authentication
* A dedicated temporary user account
* Only the permissions required for the agreed deployment
* Access removal after handover

Do not send server passwords, root passwords, private keys, seed phrases, or secret files through email, Telegram, support tickets, or GitHub.

## 4. Infrastructure Deployment

Blockiy prepares the agreed infrastructure and deploys the Cardano environment.

This stage normally includes:

* Operating-system preparation
* Security baseline and firewall configuration
* Cardano node installation and synchronization
* Block producer and relay-node configuration
* Network and P2P configuration
* Service-management and restart configuration
* Backup and recovery planning
* Basic operational health checks

## 5. Operator-Controlled Keys and Registration

All sensitive pool-key and wallet actions remain under the direct control of the operator.

Blockiy provides guidance for:

* Key-generation workflow
* Public verification-key use
* KES operational planning
* Pool registration preparation
* Metadata and configuration review

The operator performs private-key generation, signing, and wallet actions independently. Only public information required for configuration or verification should be shared.

## 6. Validation and Handover

Before handover, Blockiy performs practical checks on the deployed environment, including:

* Node synchronization status
* Relay connectivity
* Service restart behaviour
* Core network and firewall configuration
* Non-sensitive configuration review
* Basic operational health status

The operator receives the relevant handover information and guidance for ongoing operation.

## 7. Support Period

The one-year technical support period begins after the infrastructure handover is completed.

The operator can contact Blockiy for reasonable technical assistance related to the deployed infrastructure.

Support does not include guaranteed rewards, block production, delegator growth, third-party hosting outages, or changes outside the agreed infrastructure.

## Important Security Reminder

Never share:

* Wallet seed phrases
* Payment or spending signing keys
* Cold signing keys
* VRF or KES signing keys
* Encrypted key files
* Server passwords
* Private API keys or secret tokens

Read the full [Security Policy](SECURITY.md) before the setup begins.
