# Installation Guide for Wazuh Security Platform

Wazuh is a comprehensive security platform offering unified XDR and SIEM protection for endpoints and cloud workloads. It consists of a single universal agent and three central components: the Wazuh server, the Wazuh indexer, and the Wazuh dashboard. This installation guide will walk you through the process of setting up Wazuh in your infrastructure.

## Introduction

Wazuh is free and open source, licensed under the GNU General Public License version 2 and the Apache License version 2.0 (ALv2). In addition to self-hosted deployments, Wazuh also offers Wazuh Cloud, a software as a service (SaaS) solution that requires no additional hardware or software.

### Wazuh Cloud

For those looking for simplicity and convenience, Wazuh Cloud is a ready-to-use solution that reduces both cost and complexity. To learn more about Wazuh Cloud and explore the trial, refer to the Cloud service documentation.

## Installation Steps

### Installing the Wazuh Central Components

The Wazuh indexer and Wazuh server can be installed on a single host or distributed across multiple hosts in cluster configurations. You have two installation methods to choose from for each central component.

#### Quickstart Installation

For the fastest deployment, consider using the Quickstart documentation. This method provides an all-in-one installation of the Wazuh central components.

#### Custom Installation

For more deployment flexibility and customization, start with the Wazuh indexer deployment. This method allows for both all-in-one installation and deployment of components on separate servers.

Follow this installation workflow:

1. Install the Wazuh indexer.
2. Install the Wazuh server.
3. Install the Wazuh dashboard.

### Installing the Wazuh Agent

The Wazuh agent is a lightweight monitoring software that can be deployed to various platforms, including Linux, Windows, macOS, Solaris, AIX, and HP-UX. If the Wazuh central components are already installed in your environment, select your operating system below and follow the installation steps to deploy the agent on the endpoints.

- [Linux](#)
- [Windows](#)
- [macOS](#)
- [Solaris](#)
- [AIX](#)
- [HP-UX](#)

### Packages List

Refer to the Packages List section for a comprehensive list of all packages required for the installation of Wazuh.

### Other Installation Alternatives

In addition to the methods outlined in this installation guide, Wazuh provides other installation alternatives. These include deploying Wazuh using ready-to-use machines, containers, and orchestration tools. You'll also find instructions on offline installation, installation from sources, and commercial options.

---

By following this installation guide, you'll be able to set up Wazuh in your infrastructure to enhance your security posture and effectively monitor endpoints and cloud workloads. For further assistance or questions, refer to the official documentation or community forums.
