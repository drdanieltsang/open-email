# open-email

One static page, no data. A link to it carries two addresses for the same email: `g`, the Gmail web address, and
`m`, the `message://` address Apple Mail understands. On an iPhone or iPad the page forwards to Mail; anywhere else
it forwards to Gmail web. It never forwards to anything other than those two kinds of target.

Used by the Mailbox triage script (private repo) for the "open email" links it posts to Slack.
