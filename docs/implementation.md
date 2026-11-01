# Implementation notes

## 1. Purpose and scope

The Classified Multi-Vendor Ads Management Website was submitted as an undergraduate graduation project in 2023. The site demonstrates a classified-advertisement workflow, including navigation, filtering, user registration, ad submission, and account-based ad management.

## 2. Architecture and provenance

Review of the available implementation files points to a **WordPress website using the Classima theme and theme/plugin functionality**. The original thesis also discusses an HTML/CSS/JavaScript, Bootstrap, PHP, and Laravel technology stack. This should be understood as a distinction between the thesis's written description and the implementation artifacts inspected; it should **not** be taken as proof that a custom Laravel backend was implemented.

The available evidence supports the following characterization:

- **Platform:** WordPress, PHP-based CMS.
- **Presentation layer:** Classima classified-listings theme with website styling and theme templates.
- **Features:** Theme/plugin-enabled listings, user registration, filtering, and account workflows.
- **Data persistence:** WordPress-managed database and associated theme/plugin data structures; a precise live schema is not supplied in this repository.

No exact WordPress, Classima, plugin, PHP, or database version is asserted without verifiable configuration data.

## 3. Visible functional flows

1. **Discover listings:** A visitor browses the ad catalogue and searches by keyword, category or location.
2. **Create an account:** The registration screen captures account credentials and profile details.
3. **Submit an ad:** A user selects a category and enters product information, condition, price, and description.
4. **Manage ads:** The account area displays a user's listings and provides management actions.

These are functional observations from saved screenshots, not an assertion that every production path was independently retested.

## 4. Diagrams and interpretation

- **Use Case** shows the user roles and expected interactions.
- **ER Diagram** captures the proposed logical data model in the academic design.
- **DFD Level 0** gives the system-level context.
- **DFD Level 1** decomposes key management processes.
- **DFD Level 2** further expands management functions.

The diagrams are original academic planning/design figures and **do not claim to document the exact internal WordPress database tables or plugin code**. See the [README](../README.md#system-design-diagrams) to view them.

## 5. Source availability and limitations

This repository intentionally focuses on academic evidence: original thesis, screenshots, and design diagrams. A complete runnable website would also require an authorized WordPress installation, licensed theme files, compatible plugins, configuration, database content, and hosting environment. Those resources are **not included**. Avoid committing sensitive configuration, credentials, private user data, licensed vendor archives, or a full site backup to a public repository.

## 6. Thesis citation

Muntasir Md Fahim, *Classified Multi-Vendor Ads Management Website*, undergraduate graduation project, Hubei University of Technology, 2023. The original submitted report is preserved at [`Undergraduate_Thesis.pdf`](../Undergraduate_Thesis.pdf).
