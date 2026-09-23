<sub>[Documentation](README.md) › Concepts</sub>

# Concepts

The words FORGE uses, and what each one means in practice.

## Workspace

Your shop's space in FORGE. It holds your customers, jobs and quotes. Each shop's workspace is kept separate from every other shop's.

## Staff and customers

**Staff** are the people at your shop. **Customers** are the people and businesses you do work for. A customer can have a sign-in of their own, which shows only their jobs. See [Accounts and access](account-and-access.md).

## Job

One piece of work for one customer, such as a block to machine or a batch of parts to run. A job has:

| Field | Meaning |
| --- | --- |
| Job number | Assigned by FORGE when the job is created, for example `JOB-3F9A21C4` |
| Job title | A short description your team will recognise |
| Customer | Who the work is for. Set when the job is opened |
| Scope / description | What the work includes |
| Status | Where the job stands (see below) |
| Due date | When the work is due |
| Next action | The next thing that needs to happen |

## Status

| Status | Use it when |
| --- | --- |
| Intake | The job has arrived and is being assessed |
| In progress | Work is under way |
| Waiting on parts | Work is paused until parts or material arrive |
| Ready for pickup | The work is done and waiting for the customer |
| Completed | The job is closed |

## Quote revision

A quote for a job, saved as a numbered revision: revision 1, revision 2 and so on. A revision never changes once saved. To change a quote, draft a new revision. The newest revision is marked **Current**.

## Draft, issued, approved

| State | Meaning | Visible to the customer |
| --- | --- | --- |
| Draft | Saved by your team, not yet shared | No |
| Issued | Shared with the customer for review | Yes |
| Approved | Accepted by the customer | Yes |

An approval is recorded against the exact revision the customer reviewed. Approval records acceptance of the quote's scope and amount; it is not a payment.

## Related

- [Jobs](guides/jobs.md)
- [Quotes and approvals](guides/quotes-and-approvals.md)
- [Customers](guides/customers.md)
