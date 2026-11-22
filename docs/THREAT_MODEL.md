<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-BRIDGES — repository foundation
-->

# Data and authority boundaries

## Present tooling

**Execution inputs.** The maintained checkout and the selected development environment are what the repository controls inspect.

**Received inputs.** Descriptors, dependency receipts and generated inventories cannot nominate an acceptance policy or an executable.

**Bounded checks.** Controls inspect bounded local paths and emit fixed diagnostics.

Foundation qualification is in progress.

## Future domain inputs

**Supplied data, with no authority.** Records, traces, files and messages arriving from other repositories or users are supplied data. They grant no authority to publish, to claim a result, or to act for their owner.

**Comments and embedded text are data.** Descriptions and comments arriving inside supplied inputs are data, never instructions to an operator or an agent.

**Public-repository data boundary.** Hosted CI for this public repository runs on public material only. Confidential, customer, export-controlled or secret-bearing material never enters this repository, its CI or its issues.

## Threats and the rules that answer them

| Threat | Architectural rule |
| --- | --- |
| A lossy exchange presented as exact | Every exchange measures and records its loss on declared cases |
| An imported model without provenance | Every import names its source and conversion and is checked against the catalogue |
| A bridge that pulls another framework's code into the split | Bridges call other frameworks through their public interfaces and import no SC-NC repository later in the order |

**Not claimed:** no isolation, physical, statistical, safety or durability guarantee is claimed by this foundation.
