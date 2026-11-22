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

SC-NC Bridges is being built as the bridge layer split out of SC-NeuroCore: the NIR exchange bundles that carry spiking networks to and from other frameworks, the adapters that measure what an exchange loses, and the import of domain models. It imports SC-NC Core, SC-NC Catalogue, SC-NC Engine, SC-NC Data, SC-NC Compiler and SC-NC Hardware. Its current executable surface is repository validation tooling. It has no installed NIR bridge, framework adapter, model importer or qualified record schema.

Read [Architecture](ARCHITECTURE.md), [validation tooling](validation-tooling.md), [data boundaries](THREAT_MODEL.md) and the [repository boundary decision](adr/0001-repository-boundary.md).
