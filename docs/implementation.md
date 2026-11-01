# Implementation notes

## 1. Purpose and scope

The Classified Multi-Vendor Ads Management Website was submitted as an undergraduate graduation project in 2023. The site demonstrates a classified-advertisement workflow, including navigation, filtering, user registration, ad submission, and account-based ad management.

## 2. Architecture and provenance

The website files available for review show that the site uses **WordPress, the Classima theme, and related plugins**. The thesis discusses HTML, CSS, JavaScript, Bootstrap, PHP, and Laravel as well. Since the reviewed website files are WordPress-based, I have not described the project as a custom Laravel backend.

Based on the files and screenshots available:

- **Platform:** WordPress, PHP-based CMS.
- **Presentation layer:** Classima classified-listings theme with website styling and theme templates.
- **Features:** Theme/plugin-enabled listings, user registration, filtering, and account workflows.
- **Data persistence:** WordPress-managed database and associated theme/plugin data structures; a precise live schema is not supplied in this repository.

I have not listed specific software versions because I could not confirm them from the files available.

## 3. Visible functional flows

1. **Discover listings:** A visitor browses the ad catalogue and searches by keyword, category or location.
2. **Create an account:** The registration screen captures account credentials and profile details.
3. **Submit an ad:** A user selects a category and enters product information, condition, price, and description.
4. **Manage ads:** The account area displays a user's listings and provides management actions.

These features are documented from the original screenshots. I have not retested the complete website.

## 4. Diagrams and interpretation

- **Use Case** shows the user roles and expected interactions.
- **ER Diagram** captures the proposed logical data model in the academic design.
- **DFD Level 0** gives the system-level context.
- **DFD Level 1** decomposes key management processes.
- **DFD Level 2** further expands management functions.

These are diagrams from the thesis, not diagrams of the exact WordPress database or plugin code. They can be viewed in the [README](../README.md#system-design-diagrams).

## 5. Source availability and limitations

I have included the thesis, screenshots, and design diagrams to document the project. To run the website again, I would need a WordPress installation, a properly licensed theme, compatible plugins, the website database, and hosting details. Those files are not included here. Private information, passwords, and licensed third-party packages should not be uploaded to a public repository.

## 6. Thesis citation

Muntasir Md Fahim, *Classified Multi-Vendor Ads Management Website*, undergraduate graduation project, Hubei University of Technology, 2023. The original submitted report is preserved at [`Undergraduate_Thesis.pdf`](../Undergraduate_Thesis.pdf).
