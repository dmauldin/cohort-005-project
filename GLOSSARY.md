# Cadence

Cadence sells video courses to Students and lets them study them. This glossary is the shared language for the app's screens, its emails and its code.

## Language

### People

**Student**:
Someone who buys and studies courses; the only person who can request a Refund for their own Purchase.
_Avoid_: Learner, buyer, user

**Platform Admin**:
Cadence staff who run the platform, including deciding Refund Requests.
_Avoid_: Admin (on its own, since a Team Admin is someone else)

### Buying

**Purchase**:
A Student's one-off payment for one course, recording the amount paid.
_Avoid_: Order, transaction

### Refunds

**Refund Request**:
A Student's ask to get their money back for a Purchase, with their reason. It is **Open** until a Platform Admin **Approves** or **Declines** it, or the Student **Withdraws** it; after that it is closed for good. A Purchase can have many over time, but only one Open at once.
_Avoid_: Refund (for the ask itself), Cancellation, Pending Chargeback, Chargeback, Reversal, Reversal request; "Pending" or "Requested" as its state

**Refund**:
Money Cadence returns for a Purchase: exactly the amount paid for it, never partial. It comes into being only when a Refund Request is Approved, or when Cadence refunds unasked; a Declined or Withdrawn Refund Request produces no Refund.
_Avoid_: Reversal, Chargeback

**Refund Window**:
The 14 calendar days from a Purchase during which its Student may request a Refund. It limits raising a Refund Request, not deciding one.
_Avoid_: Cancel window

### Refund verbs

**Request** (a Refund):
What a Student does to raise a Refund Request.
_Avoid_: Cancel, cancel my purchase, raise a chargeback

**Approve** / **Decline**:
A Platform Admin's decision on an Open Refund Request. Approving brings a Refund into being; declining does not.

**Withdraw**:
What a Student does to close their own Open Refund Request before it is decided. Withdrawn is the Student's choice, never recorded as a decline.
_Avoid_: Cancel
