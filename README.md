# protocol-docs

Documentation for the opentxs protocol.

## Document Types

The directory [content/doctypes/](content/doctypes/) contains descriptions of
the XML structures that are created by `opentxs`. The format is described in
[Document Types](content/DocumentTypes.md).

* [Base Document Type `<Contract>`](content/doctypes/contract.md)
* [Document Type `<notaryProviderContract>`](content/doctypes/notaryProviderContract.md)
* [Document Type `<instrumentDefinition>`](content/doctypes/instrumentDefinition.md)
* [Document Type `<nymData>`](content/doctypes/nymData.md)
* [Document Type `<notaryMessage>`](content/doctypes/notaryMessage.md)
* [Document Type `<accountLedger>`](content/doctypes/accountLedger.md)
* [Document Type `<transaction>`](content/doctypes/transaction.md)
* [Document Type `<item>`](content/doctypes/item.md)
* [Document Type `<assetAccount>`](content/doctypes/assetAccount.md)

## Encoding

The encoding is detailed in the `/encoding/` directory.

* [Section Format](content/encoding/SectionFormat.md)

## Monetas Enhancement Proposals

Significant changes to the code follow a process using MEP documents
(Monetas Enhancement Proposals), stored in the [`mep`](content/mep/)
directory.

## Other documentation

The requirements for the document format and protocol are described in
[Requirements](content/Requirements.md).

The transport is described in [Transport](content/Transport.md).

Transfers are described in [Transfer](content/Transfer.md).

## Documentation Format

All documentation is written in Markdown. To help readability of text and diffs
please hard-wrap text at 72 chars, and code blocks at 79.

Please use links to commit hashes, not to branches (hit the `y` key if you are
looking at a file on Github to get a stable link).
