---
layout: default
title: BadrOS privacy policy
---

# BadrOS privacy policy

Effective date: 21 October 2026

BadrOS is a privately operated personal application, hosted on the owner's
computer. This policy describes its optional Gmail integration and associated
local storage and AI processing. This public documentation site is separate
from the private application.

## Information accessed from Google

With the account owner's authorization, BadrOS requests these Gmail permissions:

- Gmail read only access: find messages and read selected message information,
  including message identifiers, headers and available message text.
- Gmail send access: send an email containing the recipient, subject and body
  specified for that send operation.
- Optional Gmail modify access: move a specifically selected message to Gmail
  Trash. This requires an additional Google authorization; an existing
  read-and-send grant remains separate until an upgrade succeeds.

BadrOS uses this information to show selected messages, save selected text,
prepare selected text for permitted uses and carry out requested email sends.
The optional Trash action changes the selected message's mailbox state. BadrOS
does not provide a permanent-delete action. A message in Trash can be restored
using Gmail while Google still retains it; Google's own Trash retention and
deletion rules continue to apply.

The application stores the connected account address and authorization tokens
needed to identify the account and maintain the authorized connection. It does
not receive the account's Google password.

## Local storage and protection

Saved message copies, conversation history and application records are stored
on the owner's configured computer. Copies can also exist in backups controlled
by the owner. OAuth credentials are protected locally using Windows data
protection. This does not mean that every workspace file is encrypted or that
the computer is immune to compromise.

Google continues to host the Gmail mailbox. Saving a local copy does not remove
the original message from Gmail. Sending an email necessarily transmits the
message to Google and the addressed recipients.

## Limited Use and AI processing

BadrOS follows the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy)
and the
[Google Workspace API User Data and Developer Policy](https://developers.google.com/workspace/workspace-api-user-data-developer-policy),
including Limited Use, for Google-sourced information and its derivatives.

The optional summary sends the selected local message text, the owner's question
and the conversation context prepared for that question to the owner's connected
ChatGPT account. It does not automatically transmit the whole mailbox or email
attachments. Recognized Gmail copies are restricted to this ChatGPT connection,
with no automatic fallback to DeepSeek or the ordinary chat provider. This
recognition is not a universal filter for mail text manually rewritten or copied
without its Gmail source framing.

The owner must keep ChatGPT's model-improvement setting disabled for the account
used by this connection. BadrOS does not change or continuously verify that
external account setting. Google authorization alone does not approve external
AI processing. Before a different destination or materially different use is
enabled, the applicable privacy conditions must be assessed and the owner's
consent obtained.

A locally stored original does not prevent ChatGPT from processing or retaining
the copy sent to it under its applicable terms and settings. Disabling model
improvement is not a promise of zero retention or immediate downstream deletion.
BadrOS does not sell Google user data, use it for advertising, or use it to
create, train or improve generalized AI models. Those restrictions also apply
to permitted downstream processing.

## Retention and disconnection

Local saved copies and associated records remain under the owner's control.
Disconnecting the account is not a data-deletion operation. To arrange removal
of imported Gmail copies and associated records, request deletion guidance
through the contact channel below without posting private details. The
maintainer will arrange a suitable private channel and identify the affected
local copies, related conversations and backups with the owner before removal.
The current integration does not provide a one-click purge of all Gmail-derived
data. Previously created backups can retain earlier copies until those backups
are removed or expire.

Moving a message to Gmail Trash does not remove its previously saved local copy,
related conversation or backup. Those copies require separate local removal.

Disconnecting Gmail in BadrOS clears its current local authorization grant; it
does not delete previously imported message copies, conversations or backups.
The owner can also revoke BadrOS access from their Google account's third-party
connections settings. Reconnection can require a new Google authorization.

## Public documentation and contact

GitHub hosts this documentation website and handles its traffic according to
the [GitHub privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
This site has no mailbox upload form. Application credentials and private
workspace data are not published here.

For general privacy questions, use the
[documentation issue tracker](https://github.com/bam6059/badros-public-docs/issues).
It is public: do not include personal data, message contents, tokens or secrets.
Ask for a suitable private channel before discussing an individual account.

## Policy updates

Before using Google user data for a new purpose or in a materially different
way, BadrOS will explain the change and obtain the owner's consent. This policy
will be updated with a new effective date.

[Home](index.html) · [Terms of use](terms.html)
