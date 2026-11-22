<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-BRIDGES — repository foundation
-->

# SC-NC Bridges

SC-NC Bridges is being built as the bridge layer split out of SC-NeuroCore: the NIR exchange bundles that carry spiking networks to and from other frameworks, the adapters that measure what an exchange loses, and the import of domain models. It imports SC-NC Core, SC-NC Catalogue, SC-NC Engine, SC-NC Data, SC-NC Compiler and SC-NC Hardware. This checkout contains repository validation tooling and documentation only. Full foundation qualification is in progress. There is no installed NIR bridge, framework adapter, model importer or qualified record schema.

**What does not exist yet:**
- any code moved from SC-NeuroCore;
- a registered runtime record schema;
- an installed NIR bridge, framework adapter or model importer.

## Boundary

**What this project owns:**

| Record | Scope |
|---|---|
| NIR bundle | A spiking network in the NIR exchange format, with its source and target frameworks |
| External adapter loss | What an exchange with another framework loses or changes, per model and parameter |
| Domain model import | A model imported from a domain source, with its provenance and conversion |

**Static imports:** only SC-NC Core, SC-NC Catalogue, SC-NC Engine, SC-NC Data, SC-NC Compiler and SC-NC Hardware.

**Records read without importing their code:** NIR Conformance, SC-NC Compiler, Circuit Digital, Model Provenance Pack and Deploy Pack read this repository's records.

**Records it reads without importing their code:** those of SC-NC Learn, SC-NC Compiler and DIRECTOR-AI.

**Code planned to move here from SC-NeuroCore,** package by package, when SC-NeuroCore's split import gate allows it: `nir_bridge`, `adapters`, `bridges`, `integrations` and `interfaces`.

**Explicit non-claims and operating boundaries:**
- It contains no other framework; it exchanges networks with them.
- An exchange is not claimed to be lossless; its measured loss is recorded.

## Current tooling

Repository controls inspect:
- metadata and source attribution;
- workflows and dependency alignment;
- native documentation and repository inventory;
- preflight orchestration.

Metadata declares architecture-only maturity with empty implemented domain capability and claim inventories.

- Use the exact environment in [Contributing](CONTRIBUTING.md).
- Full CI and preflight belong in CI or in an explicitly admitted pre-push environment.
- See [Validation](VALIDATION.md) for the maintained validation scope.

## Intended evidence

Every future record will carry its source and environment digests, its numeric formats where it has them, and its explicit verification boundary. None of the planned record schemas is registered or qualified by this foundation.

## Documentation and support

Read [Architecture](ARCHITECTURE.md), [support](SUPPORT.md), [security reporting](SECURITY.md) and [citation metadata](CITATION.cff).

**Not claimed:**
- a hosted service, released package or DOI;
- a public CI status;
- a performed simulation, hardware measurement or benchmark result.

## Licence

Source is licensed under [AGPL-3.0-or-later](LICENSE). A commercial licence is available through the contact in [NOTICE](NOTICE.md).

![ANULUM](docs/assets/anulum_logo_company.jpg)

![Fortis Studio](docs/assets/fortis_studio_logo.jpg)

## Text and data mining reservation
The rightsholder, Miroslav Šotek (ANULUM), expressly reserves the use of the
works in this repository for text and data mining, including the collection of
this content for, and its use in, training, fine-tuning or evaluating machine
learning and artificial intelligence models, in accordance with Article 4(3) of
Directive (EU) 2019/790 and the national provisions transposing it.

No permission for such use has been granted beyond what the licence in
`LICENSE` grants. This reservation does not change that licence: uses the
licence permits remain permitted on its terms, including its attribution and
share-alike conditions.

Reservation made on 2026-11-22. Requests for permission: contact the
rightsholder through the contact listed in this repository.
