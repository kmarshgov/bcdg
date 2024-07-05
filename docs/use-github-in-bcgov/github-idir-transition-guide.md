# GitHub upgrade transition guide

This transition guide offers more detailed information about IDIRs and GitHub changes as they relate to the GitHub SSO upgrade. 

We published more about [the SSO upgrade](bc-government-organizations-in-github.md#single-sign-on-is-coming-to-the-bc-governments-github-organizations) on DevHub. 

## IDIRs

We use [Jira Service Manager](https://citz-do.atlassian.net/servicedesk/customer/portal/2) (JSM) for user requests that cannot be completed on GitHub. If there’s a topic isn’t covered in the guide, please fill out a form to open a ticket.

### Compatible IDIRs for the GitHub SSO upgrade

Our organization has many different types of IDIRs, such as:

- Primary IDIRs for employees
- Secondary IDIRs for testing
- Generic IDIRs linked to shared inboxes
- Contractor IDIRs

As we upgrade GitHub. we focus on 2 types of IDIRs:

- Primary IDIRs for employees
- Contractor IDIRs
 
### Primary IDIRs for employees
B.C. Government employees have the default configuration compatible with SSO. [DevHub has instructions to link your IDIR to GitHub](bc-government-organizations-in-github.md#single-sign-on-is-coming-to-the-bc-governments-github-organizations).
 
### Compatible IDIRs for contractors
If a user is a contracted worker, then the process may be more complex, depending on IDIR types. The table below offers an overview between P2 and E5, IDIRs compatible with the GitHub SSO upgrade.
We don’t foresee any technical issues with SSO if contractors have either IDIR type. If this isn’t the case, please fill out a form to open a ticket on [our Jira Service Manager](https://citz-do.atlassian.net/servicedesk/customer/portal/2).
 
P2 and E5 IDIR comparison
Column 1 lists IDIR features, column 2 has P2 features, and column 3 has E5 features.
 

|                     | P2 IDIR       | E5 IDIR       |
|---------------------|---------------|---------------|
| Cost                | $2 per month  | $57 per month |
| Office 365 license  | No            |  Yes          |
| Expiry date         | Yes           |  Yes          |


Please see [Service Bulletin 1350](https://ociomysc.service-now.com/sp?id=kb_article&sys_id=7a69f65fdbff9d10fa86193813961978&spa=1) for more information.

Contract managers must keep expiry dates updated because our team doesn’t have the ability to submit orders on behalf of ministries. 

It’s very likely contractors already with IDIRs have P2. If linking doesn't work, please call 7-7000 or open a ticket to confirm through [MyService Centre](https://ociomysc.service-now.com/sp?id=ocio_sr_incident_management).
 
### Contractors without IDIRs
Each ministry has an authorized user who submits orders in [MyService Centre](https://ociomysc.service-now.com/sp?id=ocio_sr_incident_management). Please reach out to them as soon as possible to order an IDIR.
Multiple IDIRs.

Developers with multiple IDIRs can link their most permanent IDIR to their GitHub ID. They can change IDIRs at any time. We tested and can confirm that users make changes on their own.

The important things to keep in mind are:

- The IDIR must not be expired
- Our team cannot manage IDIR expiry dates
 
If you don’t see information that could be helpful on this guide, please let us know through [our Jira Service Manager](https://citz-do.atlassian.net/servicedesk/customer/portal/2).

