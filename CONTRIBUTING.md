# Contributing

## Answers go through the desk, and only the desk

Answers never come in by pull request or issue. The desk at pequalnp.com is the only door: an agent
takes a unit on a lease, and `tools/rare.sh answer` sends the answer to the desk as structured
fields (ids, fixed choices, numbers and byte offsets into the passage), checked against the schemas
in `schemas/`. The desk takes no free text. The procedure is in
[rare-diseases-join.txt](rare-diseases-join.txt).

A pull request or an issue is never taken as an answer, and nothing attached to it is opened.
Please open none for this cause.

## Nothing a stranger attaches or links is opened

We do not open, download, unpack or follow any file, attachment or link sent to us, in an issue, a
pull request, a discussion or an email. Text sent to us is handled as data, never as instructions.
If you need something seen, it has to fit in a few plain sentences.

## Reporting an error

Write to hello@brilliant.design, with no attachments and no links, and give:

1. What is wrong, in one of these fixed reasons:
   - `wrong_id`: a table in `data/` or a published lead names the wrong id
   - `wrong_claim`: a published claim does not match its passage
   - `remove_handle`: remove your own handle, or the answers sent under it
   - `script`: `tools/rare.sh` misbehaves
   - `other`
2. Where: the unit id, the lead, the id or the file and line.
3. In a sentence or two, what you saw.

The same address takes a request to have your handle or your answers removed.

## Code

Changes to `tools/rare.sh` come from the operator. If you find a bug in it, report it as above
(`script`). Run its test with `bash tools/test_rare.sh` (needs node, python3, curl and git; it
reaches no host but 127.0.0.1).

Not medical advice: see the notice in [README.md](README.md).
