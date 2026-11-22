<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-BRIDGES — repository foundation
-->

# Repository architecture

## Current executable tooling

**What it contains:** the repository's metadata, source-provenance, workflow, dependency-alignment, documentation, inventory and preflight controls.

**What each control does:** it inspects its fixed, declared local scope.

**What received metadata cannot do:** select another acceptance policy or grant domain authority.

Foundation qualification is in progress.

## Intended domain boundaries

| Record | Responsibility | Required evidence |
| --- | --- | --- |
| NIR bundle | A spiking network in the NIR exchange format, with its source and target frameworks | Round trip through the bundle, with every difference recorded |
| External adapter loss | What an exchange with another framework loses or changes, per model and parameter | Loss measured on declared cases, never assumed to be zero |
| Domain model import | A model imported from a domain source, with its provenance and conversion | Import checks against the source and the catalogue |

## Planned record schemas

- `sc_nc_bridges.nir_bundle.v1`
- `sc_nc_bridges.external_adapter_loss.v1`
- `sc_nc_bridges.domain_model_import.v1`

These are planned identifiers. None of them is registered or qualified here.

Read [validation tooling](validation-tooling.md) for the executable repository interfaces.
