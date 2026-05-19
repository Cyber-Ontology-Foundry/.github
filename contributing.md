# Contributing to the Cyber Ontology Foundry

Thank you for your interest in contributing to the Cyber Ontology Foundry.

The Cyber Ontology Foundry exists to develop, maintain, and coordinate open, interoperable, formally grounded ontologies for the cyber domain. Contributions should help make cyber data, standards, systems, observations, controls, vulnerabilities, incidents, threats, evidence, and claims more explicit, comparable, reusable, and machine-interpretable.

The Foundry does **not** aim to replace existing cyber standards. It aims to provide a formal semantic layer that helps align, clarify, validate, and reason across them.

This document explains how to:

- submit an ontology for Foundry review;
- contribute to an existing Foundry ontology;
- request new terms, definitions, relations, mappings, design patterns, use cases, and documentation changes;
- understand how Foundry review works;
- avoid security, sensitivity, licensing, and governance problems.

---

## 1. Contribution principles

All contributions should support the Foundry’s core goals.

1. **Openness**  
   Public Foundry artifacts should be available for reuse, review, implementation, and extension.

2. **Formalization**  
   Ontology content should be represented in standard machine-readable ontology languages, with OWL 2 as the minimum formal target for official Foundry ontology modules unless an exception is approved.

3. **Clear scope**  
   Every proposed ontology, module, class, relation, mapping, or pattern should say what it covers and what it does not cover.

4. **Reuse before invention**  
   Contributors should check existing Foundry content and relevant external ontologies before creating new terms.

5. **Stable identifiers**  
   Official ontology terms must use managed, persistent identifiers.

6. **Clear definitions**  
   Classes and relations should have precise textual definitions, preferably in genus-differentia form.

7. **Validation**  
   Ontology changes should pass syntax, consistency, satisfiability, and structural quality checks.

8. **Justification**  
   Definitions, mappings, and modeling decisions should be justified by use cases, source standards, examples, competency questions, or other evidence.

9. **Governance**  
   Official content must be reviewed and approved through the Foundry’s governance process.

10. **Responsiveness**  
   Contributors and maintainers should treat issues and pull requests as serious community contributions.

---

## 2. Contents

Use this page to find the right contribution path.

- [3. Choose the right contribution path](#3-choose-the-right-contribution-path)
- [4. Basic rules for all contributions](#4-basic-rules-for-all-contributions)
- [5. Submit an ontology for Foundry review](#5-submit-an-ontology-for-foundry-review)
  - [5.1 Possible review outcomes](#51-possible-review-outcomes)
  - [5.2 What to include with an ontology submission](#52-what-to-include-with-an-ontology-submission)
  - [5.3 Minimum expectations for submitted ontologies](#53-minimum-expectations-for-submitted-ontologies)
- [6. Contribute to an existing Foundry ontology](#6-contribute-to-an-existing-foundry-ontology)
  - [6.1 Start with an issue](#61-start-with-an-issue)
  - [6.2 Request a new term](#62-request-a-new-term)
  - [6.3 Improve a definition](#63-improve-a-definition)
  - [6.4 Propose a new relation](#64-propose-a-new-relation)
  - [6.5 Propose a mapping to an external standard](#65-propose-a-mapping-to-an-external-standard)
  - [6.6 Contribute a design pattern](#66-contribute-a-design-pattern)
  - [6.7 Add a use case or competency question](#67-add-a-use-case-or-competency-question)
  - [6.8 Report an ontology bug](#68-report-an-ontology-bug)
  - [6.9 Improve documentation](#69-improve-documentation)
- [7. Pull request expectations](#7-pull-request-expectations)
- [8. How review works](#8-how-review-works)
- [9. Versioning, releases, and deprecation](#10-versioning-releases-and-deprecation)
- [10. Security and sensitive content](#11-security-and-sensitive-content)
- [11. Licensing and intellectual property](#12-licensing-and-intellectual-property)
- [12. Communication norms](#13-communication-norms)
- [13. Working group and Steering Committee review](#15-working-group-and-steering-committee-review)

---

## 3. Choose the right contribution path

There are two main ways to contribute.

### A. Submit a whole ontology for Foundry review

Use this path if you want the Foundry to review an ontology as a whole.

This includes requests to have an ontology:

- accepted as an official Cyber Ontology Foundry module;
- treated as a mapping or reference ontology;
- placed in experimental, provisional, or incubator status.

Start by opening an **Ontology Submission** issue.

### B. Contribute to an existing Foundry ontology

Use this path if you want to improve something already in the Foundry.

You can, among other things:

- request a new ontology term;
- improve a definition;
- propose a new relation;
- report duplicate or overlapping terms;
- propose a mapping to an external standard;
- contribute a design pattern;
- add a competency question;
- add a use case or example;
- report an ontology bug;
- improve documentation;
- review existing issues and pull requests;
- participate in a working group.

Start by opening the relevant issue type.

All substantive contributions should begin with an issue unless a maintainer has explicitly directed otherwise.

---

## 4. Basic rules for all contributions

Before submitting anything, please follow these rules.

1. **Start with an issue.**  
   Open an issue before making a major pull request.

2. **Explain the use case.**  
   Tell us what problem the contribution helps solve.

3. **Check for existing terms.**  
   Do not create a new term if an existing Foundry term already covers the meaning.

4. **Use clear definitions.**  
   Definitions should say what kind of thing the term is and how it differs from nearby terms.

5. **Provide examples and boundary cases.**  
   Examples help reviewers understand what should and should not fall under a term.

6. **Include sources or provenance.**  
   Tell us where the term, mapping, or modeling decision comes from.

7. **Consider security.**  
   Do not submit classified, controlled, proprietary, exploit-enabling, or otherwise sensitive material.

8. **Be prepared for review.**  
   Foundry content must be reviewed before it becomes official.

9. **Avoid unnecessary duplication.**  
   Reuse existing Foundry terms, relations, patterns, and modules whenever possible.

10. **Document semantic gaps.**  
   If a mapping or reuse decision is approximate, say so clearly.

---

## 5. Submit an ontology for Foundry review

The Cyber Ontology Foundry accepts ontology submissions for review.

Submitting an ontology does **not** mean the ontology is automatically accepted. Review determines whether the ontology is in scope, technically sound, well-documented, reusable, appropriately governed, and safe for public release.

Open an **Ontology Submission** issue if you want the Foundry to review an ontology.

### 5.1 Possible review outcomes

A submitted ontology may receive one of the following outcomes.

| Outcome | Meaning |
|---|---|
| **Official COF ontologye** | The ontology becomes part of the official Cyber Ontology Foundry suite. |
| **Mapping/reference ontology** | The ontology is not adopted as a COF ontology but may be mapped to or referenced by COF. |
| **Experimental or provisional ontology** | The ontology may be discussed, tested, or incubated but is not yet official. |
| **Deferred** | The ontology may be reconsidered later after additional work. |
| **Rejected** | The ontology is out of scope, duplicative, insufficiently documented, technically unsound, incompatible with Foundry principles, or unsuitable for public release. |

Submission does not imply acceptance.

### 5.2 What to include with an ontology submission

An ontology submission should include the following information.

| Required item | What to provide |
|---|---|
| **Ontology title** | Full name of the ontology. |
| **Short name or acronym** | The short name, acronym, or common name. |
| **Short description** | One paragraph explaining what the ontology covers. |
| **Repository or download location** | Link to the ontology files. |
| **Issue tracker** | Link to the public issue tracker. |
| **Primary contact** | Name and contact information for the submitter. |
| **Maintainers** | Names of current maintainers. |
| **License** | The license under which the ontology is released. |
| **Formats** | Available formats, such as OWL, Turtle, RDF/XML, JSON-LD, or OBO. |
| **Requested prefix** | Requested prefix or identifier space. |
| **Current version** | Current release version, if any. |
| **Development version** | Development branch or version, if different from the release. |
| **Documentation location** | Link to README, scope notes, examples, and other documentation. |
| **Scope** | What the ontology covers. |
| **Out of scope** | What the ontology intentionally does not cover. |
| **Intended users** | Who is expected to use the ontology. |
| **Use cases** | Concrete problems the ontology is meant to support. |
| **Competency questions** | Questions the ontology should help answer. |
| **External standards** | Standards, schemas, taxonomies, or resources reused or mapped. |
| **Known overlaps** | Related ontologies or modules that may overlap. |
| **Maintenance plan** | Who will maintain the ontology and how. |
| **Release plan** | How releases are versioned and documented. |
| **Deprecation plan** | How obsolete or replaced terms are handled. |
| **Security assessment** | Confirmation that the ontology does not contain sensitive content. |

Strong submissions may also include:

- automated quality-control workflow;
- ROBOT or equivalent build workflow;
- reasoner results;
- import strategy;
- term tracker or issue labels;
- definition policy;
- identifier policy;
- deprecation policy;
- changelog;
- example data;
- SPARQL competency-question queries;
- SHACL shapes;
- mapping tables to cyber standards;
- evidence that the ontology is already used by more than one project, organization, or community.

### 5.3 Minimum expectations for submitted ontologies

Submitted ontologies should meet these expectations before review.

| Requirement | What it means |
|---|---|
| **Public availability** | The ontology should be publicly available unless a restricted review process has been approved. |
| **Open license** | Public Foundry ontologies should use a license suitable for reuse, review, implementation, and extension. |
| **Machine-readable format** | The ontology should be available in a standard ontology format. OWL 2 is the minimum target for official COF modules unless an exception is approved. |
| **Clear scope** | The ontology must say what it covers and what it does not cover. |
| **Stable identifiers** | Terms must use stable IRIs under an approved prefix or identifier space. |
| **Definitions** | Major classes and relations should have clear textual definitions. |
| **Logical quality** | The ontology should parse, imports should resolve, and there should be no unintended unsatisfiable classes. |
| **Documentation** | The ontology should have a README, scope note, examples, contribution guidance, release notes, and known limitations. |
| **Maintenance** | The ontology must have named maintainers and a clear maintenance process. |
| **Security** | The ontology must not disclose classified, controlled, proprietary, exploit-enabling, or otherwise sensitive content. |

---

## 6. Contribute to an existing Foundry ontology

Use this section if you want to improve an ontology that is already part of the Foundry.

### 6.1 Start with an issue

Before opening a pull request, open an issue in the appropriate repository.

Use the relevant issue template when available:

- **Term Request**
- **Definition Revision**
- **Relation Request**
- **Mapping Request**
- **Design Pattern Proposal**
- **Use Case / Competency Question**
- **Documentation Issue**
- **Ontology Bug Report**
- **Security or Sensitive Content Review**
- **New Module Proposal**

A good issue should include enough information for maintainers to understand the need, evaluate scope, and determine whether existing Foundry content already covers the request.

### 6.2 Request a new term

Open a **Term Request** issue.

Include:

- proposed label;
- requested ontology or module;
- plain-language explanation;
- proposed definition, if available;
- use case or competency question;
- examples;
- counterexamples or boundary cases;
- source or provenance;
- related external standard, if any;
- relationship to existing Foundry terms;
- security or sensitivity concerns.

Example:

```text
Label:
  vulnerability

Proposed definition:
  A realizable weakness in a system, software artifact, configuration, process, or organization that can be exploited under some conditions.

Use case:
  Analysts need to connect CVE records, affected software, exploit availability, mitigations, and observed incidents.

Competency question:
  Which vulnerabilities affect assets used by this organization and have known exploit techniques?

Examples:
  CVE-listed software vulnerability; misconfiguration; exposed credential; insecure default setting.

Counterexamples:
  An actual exploit event; a threat actor; a patch; a control objective.

Sources:
  CVE, CWE, NIST, CISA, internal Foundry discussion.

Security concerns:
  Do not include unreleased exploit details or target-specific operational information.
```

### 6.3 Improve a definition

Open a **Definition Revision** issue.

Include:

- the current term;
- the current definition;
- the proposed revised definition;
- the reason for the change;
- examples or counterexamples;
- any source or provenance;
- whether the change affects existing use.

Definitions should be clear, non-circular, and useful to both cyber experts and ontology maintainers.

Preferred form:

```text
A is a B that Cs.
```

Definitions should:

- state what kind of thing the term names;
- distinguish the term from neighboring terms;
- avoid circularity;
- avoid merely restating the label;
- avoid unexplained acronyms;
- avoid vendor-specific jargon unless the term is explicitly vendor-specific;
- avoid metaphorical language;
- avoid definitions that depend on a particular tool, product, platform, or schema.

Avoid definitions like:

```text
A vulnerability is when something is vulnerable.
A cyber incident is a bad cyber thing.
A control is something from NIST 800-53.
A threat actor is an APT.
```

### 6.4 Propose a new relation

Open a **Relation Request** issue.

Include:

- proposed relation label;
- plain-language meaning;
- examples;
- counterexamples;
- proposed domain and range, if known;
- existing relations considered;
- why existing relations are insufficient;
- proposed parent relation, if known;
- expected reasoning or query behavior.

New relations require careful review because relation duplication can damage interoperability.

Before proposing a new relation:

1. Check existing Foundry relations.
2. Check imported or aligned ontology relations.
3. Check whether a relation from BFO, CCO, RO, IAO, or another approved ontology already covers the intended meaning.
4. Explain why an existing relation is insufficient.
5. If proposing a narrower cyber-specific relation, identify its broader parent relation.

### 6.5 Propose a mapping to an external standard

Open a **Mapping Request** issue.

Include:

- source standard;
- source version;
- source term, class, field, object, or relationship;
- target Foundry term;
- proposed mapping type;
- explanation of the mapping;
- known mismatch or semantic loss;
- source or provenance;
- license or reuse constraints.

The Foundry may map to resources such as:

- STIX/TAXII;
- MITRE ATT&CK;
- D3FEND;
- CAPEC;
- CVE;
- CWE;
- CPE;
- NIST Cybersecurity Framework;
- NIST SP 800-53;
- OSCAL;
- CIS Controls;
- Sigma;
- YARA;
- OpenCTI;
- other relevant standards, schemas, taxonomies, or knowledge resources.

Do not claim an exact mapping unless the meanings are genuinely equivalent.

Use weaker mappings when needed:

- exact match;
- close match;
- broad match;
- narrow match;
- related match;
- informative reference.

Example:

```text
ATT&CK technique X is not identical to COF class Y. ATT&CK represents operational technique knowledge, while COF class Y represents a type of process. The mapping is therefore close or related, not exact.
```

### 6.6 Contribute a design pattern

Open a **Design Pattern Proposal** issue.

Include:

- pattern name;
- problem addressed;
- scope;
- competency questions;
- informal explanation;
- ontological analysis;
- classes involved;
- relations involved;
- example representation;
- OWL axioms, if appropriate;
- SPARQL examples, if appropriate;
- SHACL examples, if appropriate;
- boundary cases;
- related standards;
- known limitations.


### 6.7 Add a use case or competency question

Open a **Use Case / Competency Question** issue.

A competency question is a question the ontology should help answer.

Examples:

```text
Which vulnerabilities affect systems used by a given organization?

Which mitigations address vulnerabilities exploited by a given technique?

Which incidents involved assets running software with a known vulnerable version?

Which observations support an attribution claim?

Which controls reduce the likelihood of successful credential theft?

Which cyber operations depended on access to a compromised account?
```

Good competency questions help reviewers determine:

- whether a proposed term is needed;
- whether the proposed modeling is sufficient;
- which relations are required;
- which external mappings matter;
- which examples should be tested;
- which SPARQL queries or validation checks should be added.

### 6.8 Report an ontology bug

Open an **Ontology Bug Report** issue.

Examples of ontology bugs include:

- broken imports;
- unsatisfiable classes;
- duplicate labels;
- missing definitions;
- incorrect hierarchy;
- incorrect mapping;
- unclear scope;
- identifier errors;
- unintended reasoning results;
- deprecated term misuse.

### 6.9 Improve documentation

Open a **Documentation Issue** or submit a focused pull request.

Useful documentation improvements include:

- clearer scope notes;
- examples;
- counterexamples;
- competency questions;
- modeling rationale;
- design pattern explanations;
- mapping notes;
- release notes;
- migration notes;
- known limitations;
- contributor guidance.

Documentation should distinguish:

- normative ontology content;
- informative examples;
- draft proposals;
- experimental patterns;
- external mappings;
- deprecated content.

---

## 7. Pull request expectations

Pull requests should be focused and reviewable.

A good pull request:

- addresses a linked issue;
- makes one coherent change;
- includes definitions for new terms;
- includes provenance where needed;
- adds examples or competency questions where appropriate;
- updates documentation when behavior or scope changes;
- passes automated checks;
- avoids unrelated formatting churn;
- flags security or sensitivity issues.

---

## 8. How review works

Most contributions follow this process.

1. **Issue opened**  
   The contributor opens the appropriate issue.

2. **Triage**  
   Maintainers decide whether the issue is complete, in scope, and assigned to the right repository or working group.

3. **Discussion**  
   Contributors, maintainers, and working groups discuss the issue.

4. **Pull request**  
   If a change is accepted in principle, the contributor or maintainer opens a pull request.

5. **Automated checks**  
   The ontology is checked for syntax, imports, consistency, identifiers, missing labels, missing definitions, and related quality issues.

6. **Manual review**  
   Reviewers check scope, definitions, axioms, mappings, documentation, security, and governance implications.

7. **Decision**  
   The contribution is accepted, accepted with revisions, deferred, rejected, or escalated for further review.

8. **Merge and release**  
   Accepted changes are merged and included in a future release.

Major changes may require working group review or Steering Committee review.

## 9. Versioning, releases, and deprecation

Official releases should be versioned, archived, and documented.

A release should include:

- release tag;
- version IRI, when applicable;
- release date;
- release notes;
- changelog;
- list of major changes;
- list of breaking changes;
- migration notes, when needed;
- generated ontology artifacts;
- quality-control results;
- known issues.

Do not treat the development branch as a stable release.

Downstream users should be able to identify exactly which ontology version they used.

### Deprecation

Terms should not be deleted casually.

When a term is obsolete, deprecated, replaced, or merged:

- preserve the identifier;
- mark the term as deprecated or obsolete;
- explain why it was deprecated;
- identify replacement terms when available;
- add migration guidance;
- avoid reusing the identifier for another meaning.

Changing the meaning of an existing term can break downstream systems. Major meaning changes require review.

---

## 10. Security and sensitive content

Because the Foundry operates in the cyber domain, contributors must take special care.

Do **not** submit:

- classified information;
- controlled unclassified information without authorization;
- proprietary information without permission;
- unreleased vulnerability details;
- exploit-enabling operational details;
- target-specific operational information;
- sensitive personal information;
- sensitive organizational information;
- credentials, keys, tokens, or secrets.

When in doubt, do not post the information publicly.

Open a security review request or contact the designated maintainers through the appropriate non-public channel.

Public reference ontologies should remain open wherever possible. Restricted operational extensions may exist, but they should preserve compatibility with the public core and must not leak sensitive content into public repositories.

---

## 11. Licensing and intellectual property

By contributing, you agree that your contribution may be distributed under the license used by the relevant repository.

Do not contribute content you do not have the right to contribute.

Do not copy definitions, documentation, diagrams, schema text, or standard text from external sources unless:

- the license permits reuse;
- attribution is provided where required;
- reuse is compatible with the Foundry license;
- maintainers approve the inclusion.

When using external standards as sources, prefer paraphrase, mapping, citation, and semantic analysis over verbatim copying.

---

## 12. Communication norms

Participants should:

- be respectful and precise;
- assume good faith;
- distinguish technical disagreement from personal criticism;
- explain objections clearly;
- provide examples when possible;
- avoid dismissive comments;
- be willing to revise proposals;
- record decisions in public issues when appropriate.

Ontology engineering often involves difficult boundary cases. Disagreement is expected. The goal is to make decisions explicit, justified, and reviewable.

---

## 13. Working group and Steering Committee review

Some issues require working group review.

Examples include:

- new ontology submissions;
- new module proposals;
- major architectural changes;
- new relation proposals;
- cross-module modeling conflicts;
- large mapping efforts;
- design patterns likely to affect many modules;
- security-sensitive material;
- major release decisions.

Working group outputs become official Foundry outputs only after approval under the relevant governance procedure.

The Steering Committee or delegated governance body may be required for:

- changes to Foundry scope;
- changes to Founding Principles;
- recognition of official Foundry ontology modules;
- approval of public releases;
- major licensing changes;
- creation or dissolution of working groups;
- appointment of module maintainers;
- public communications issued on behalf of the Foundry.

Routine term, definition, mapping, and documentation changes normally do not require Steering Committee review unless they raise broader governance, scope, licensing, or security issues.

---

Thank you for helping build a shared semantic foundation for the cyber domain.