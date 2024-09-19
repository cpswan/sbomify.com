---
layout: page
permalink: /resources/
title: SBOM Resources

---

The SBOM life cycle can be broken down into three phases: [generation, distribution, and analysis]({{ site.url }}/features/generate-collaborate-analyze/). The structure below aligns with the life cycle.

There's also a GitHub repository called [sbom-benchmarks](https://github.com/sbomify/sbom-benchmarks) that sets to benchmark the various tools (from the Generation phase) against each other, along with providing examples how they are used.

## Generation / Authoring

The SBOM generation phase, also known as authoring, is where you create an SBOM from a source. There are various strategies for generating SBOMs, but this phase generally involves taking a set of inputs (such as a dependency file) and generating an SBOM in either the [CycloneDX](https://cyclonedx.org/) or [SPDX](https://spdx.dev/) format.

### Generic

Tools that spans multiple formats and languages.

* [Snyk](https://github.com/snyk/cli) from Snyk
* [Syft](https://github.com/anchore/syft) from Anchore
* [Trivy](https://github.com/aquasecurity/trivy) from Aqua

### Specific

Language or format-specific tools.

#### Docker / Containers

You can see how they compare side-by-side in the [sbom-benchmark](https://github.com/sbomify/sbom-benchmarks/tree/master/docker) repository.

* [Tern](https://github.com/tern-tools/tern)
* [bom](https://github.com/kubernetes-sigs/bom) from The Linux Foundation

#### Python

You can see how they compare side-by-side in the [sbom-benchmark](https://github.com/sbomify/sbom-benchmarks/tree/master/python) repository.

* [CycloneDX Python](https://github.com/CycloneDX/cyclonedx-python) from CycloneDX
* [sbom4python](https://github.com/anthonyharrison/sbom4python) from Anthony Harrison
* [SPDX Python](https://github.com/spdx/tools-python) from SPDX

#### Rust

* [CycloneDX Rust](https://github.com/CycloneDX/cyclonedx-rust-cargo) from CycloneDX
* [sbom-rs](https://github.com/psastras/sbom-rs) from Paul Sastrasinh
* [sbom4rust](https://github.com/anthonyharrison/sbom4rust) from Anthony Harrison

#### Go

* [CycloneDX Go](https://github.com/CycloneDX/cyclonedx-gomod) from CycloneDX
* [SPDX Golang](https://github.com/spdx/tools-golang) from SPDX

#### .NET

* [CycloneDX .NET](https://github.com/CycloneDX/cyclonedx-dotnet-library) from CycloneDX
* [SBOM Tool](https://github.com/microsoft/sbom-tool) from Microsoft

#### Java

* [CycloneDX Java](https://github.com/CycloneDX/cyclonedx-core-java) from CycloneDX
* [SPDX Java](https://github.com/spdx/Spdx-Java-Library) from SPDX

#### JavaScript

* [CycloneDX JavaScript](https://github.com/CycloneDX/cyclonedx-javascript-library)
* [Retire.js](https://github.com/RetireJS/retire.js) from RetireJS
* [sbom4js](https://github.com/anthonyharrison/sbom4js) from Anthony Harrison

#### Others

* [protobom](https://github.com/protobom/protobom)
* [Hoppr](https://hoppr.dev/) from Lockheed Martin Corporation
* [OSS Review Toolkit](https://github.com/oss-review-toolkit/ort) (ORT)

### Assembly and Enrichment

* [CycloneDX Editor/Validator](https://github.com/Festo-se/cyclonedx-editor-validator/) from Festo
* [Parlay](https://github.com/snyk/parlay) from Snyk
* [jq](https://github.com/jqlang/jq) is commonly used for assembly
* [sbomasm](https://github.com/interlynk-io/sbomasm) from Interlynk
* [sbomaudit](https://github.com/anthonyharrison/sbomaudit) from Anthony Harrison

## Distribution / Transportation

The distribution phase, also known as Transportation, focuses on how you share the SBOM with internal and external stakeholders.

* [sbomify]({{ site.url }})
* [Project Koala](https://github.com/CycloneDX/transparency-exchange-api) (a.k.a. Transparency Exchange API) from CycloneDX

## Analysis

The analysis phase involves how you use the SBOM, typically for compliance or security purposes. Mature organizations may use multiple tools or services for different purposes.

* [Cybellum](https://cybellum.com/) from Cybellum
* [Dependency Track](https://dependencytrack.org/) from OWASP
* [Eclipse SW360](https://github.com/eclipse-sw360/sw360)
* [GUAC](https://guac.sh) from OpenSSF
* [Helm](https://www.medcrypt.com/solutions/helm) from Medcrypt
* [NTIA Conformance Checker](https://github.com/spdx/ntia-conformance-checker) from SPDX
* [Open Source Vulnerabilities](https://osv.dev/) (OSV) from Google
* [bomber](https://github.com/devops-kung-fu/bomber) from DKFM
* [bomshell](https://github.com/puerco/bomshell) from Adolfo García Veytia (a.k.a. Puerco)
* [grype](https://github.com/anchore/grype) from Anchore
* [sbomaudit](https://github.com/anthonyharrison/sbomaudit) from Anthony Harrison
* [sbommerge](https://github.com/anthonyharrison/sbommerge) from Anthony Harrison
* [sbomqs](https://github.com/interlynk-io/sbomqs) from Interlynk
* [SecObserve](https://github.com/MaibornWolff/SecObserve) from MaibornWolff

## Other SBOM resources

* CISA's [SBOM Sharing Primer](https://www.cisa.gov/sites/default/files/2024-05/SBOM%20Sharing%20Primer.pdf)
* CISA's [Software Bill of Materials (SBOM) Sharing Lifecycle Report](https://www.cisa.gov/sites/default/files/2023-04/sbom-sharing-lifecycle-report_508.pdf)
* NTIA's [Framing Software Component Transparency: Establishing a Common Software Bill of Materials (SBOM)](https://www.ntia.gov/sites/default/files/publications/ntia_sbom_framing_2nd_edition_20211021_0.pdf) (2nd Edition)
* NTIA's [The Minimum Elements For a Software Bill of Materials (SBOM)](https://www.ntia.gov/sites/default/files/publications/sbom_minimum_elements_report_0.pdf)

[Edit me on GitHub](https://github.com/sbomify/sbomify.com/blob/master/resources.md)
