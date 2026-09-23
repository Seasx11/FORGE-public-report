<sub>[Documentation](../README.md) › [Guides](../README.md#guides) › Quotes and approvals</sub>

# Quotes and approvals

Quotes in FORGE belong to a job. Each one is saved as a numbered revision that never changes, so you and your customer can always tell which version was reviewed and which was approved.

<img src="../../assets/guides/quote-history.png" alt="A job page with its scope, next action and due date beside an approved quote revision." width="100%">

## Draft a quote

1. Open the job and select **＋ Draft quote**.
2. Fill in the form:

   | Field | Required | Notes |
   | --- | --- | --- |
   | Scope | Yes | What the quote covers |
   | Reference | No | Your own quote number or note |
   | Line item | Yes | In the preview, a draft has one line item |
   | Quantity | Yes | A whole number, 1 or more |
   | Unit price (USD) | Yes | Up to two decimal places, for example `1280.00` |

3. Select **Create draft**.

The draft is saved as the next revision (revision 1, revision 2 and so on) and marked **Current**. The total can be up to $1,000,000.00.

A draft is visible only to your team.

## Issue a quote

When the current draft is ready for your customer, select **Issue to customer** on the quote. FORGE confirms *Quote issued. It is now available to the assigned customer.*

Only the newest draft can be issued. If you see *Latest draft required.*, refresh the job page and issue the revision marked **Current**.

## Change a quote

A revision never changes once saved. To change the scope or price, draft a new revision and issue it. Earlier revisions stay on the job page as a record of what was proposed, and your customer keeps seeing every revision you issued.

As soon as you draft a new revision, the previously issued one can no longer be approved. Your customer can approve again once you issue the new revision.

## Customer approval

Your customer signs in, opens the job, and selects **Review approval** on the issued quote. FORGE shows the revision number, total and scope, and reminds them:

> Approval records your acceptance of this quote's scope and amount. It does not make a payment.

When they select **Approve quote**, the approval is recorded against that revision and the quote shows **Approved** on your job page.

<img src="../../assets/guides/customer-approval.gif" alt="A customer signs in, opens their engine job, reviews the issued quote and approves it." width="100%">

A customer can approve only the newest revision, once it has been issued. If they see *Latest issued quote required.*, your team has drafted a newer revision since they opened the page. They can approve once you issue it.

## Related

- [Jobs](jobs.md)
- [Customers](customers.md)
- [Concepts](../concepts.md#draft-issued-approved)
