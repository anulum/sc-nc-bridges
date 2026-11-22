<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-BRIDGES — repository foundation
-->

# Architecture

## Current executable surface

The checkout contains:
- repository validation tooling;
- dedicated tests;
- workflow definitions;
- native documentation.

No domain component of SC-NC Bridges is implemented yet, and no code has moved here from SC-NeuroCore. The metadata keeps domain capabilities, claims and qualified record formats empty.

## Intended records

1. **NIR bundle:** A spiking network in the NIR exchange format, with its source and target frameworks.
2. **External adapter loss:** What an exchange with another framework loses or changes, per model and parameter.
3. **Domain model import:** A model imported from a domain source, with its provenance and conversion.

## Ownership

**This project owns** the planned SC-NC Bridges records and boundary rules.

**Owned elsewhere:**

| Responsibility | Owner |
|---|---|
| models and descriptors | SC-NC Catalogue |
| conformance of exchange bundles | NIR Conformance |
| compilation | SC-NC Compiler |
| the public package, documentation and releases of the monolith | SC-NeuroCore |

## Interpretation

- **Exchange.** A bridge's result is bounded by its measured loss.
- **Moves.** Code arrives only through SC-NeuroCore's split import gate, unit by unit; a planned move is not a moved capability.

Read [the documentation architecture](docs/ARCHITECTURE.md) for the planned records, rules and schema identifiers.
