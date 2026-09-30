# Public Release Audit — v1.1

Date: 30 September 2026

## Scope and confidentiality

**PASS**

The public package does not disclose:

- the sample size or sampling design of the separate research project;
- confidential fieldwork arrangements;
- research-project budgets;
- named internal project personnel;
- private operationalization materials;
- full internal indicator systems;
- the full granular measure registry;
- numerical normative weights;
- detailed labor-hour estimates.

The page explicitly states that it is not a representation of confidential project data.

## Empirical overclaim

**PASS**

The public version states that:

- diagnostic profiles are illustrative configurations;
- they are not classifications of actual TOS organizations;
- prevalence has not been estimated in the prototype;
- individual pathways require empirical testing;
- successful pilots should not be generalized automatically.

## Institutional accuracy

**PASS WITH CONTINUING LEGAL-REVIEW REQUIREMENT**

The public version distinguishes:

- resident self-organization;
- municipal procedures and authority;
- regional support conditions.

It does not describe TOS bodies as subordinate regional administrative units.

Any real-world implementation would still require checking the applicable consolidated legal text and local municipal acts at the time of use.

## Recommendation-engine risk

**PASS**

The interface does not accept a real organization's data and does not output an automated diagnosis or intervention recommendation.

Interactions are explicitly illustrative.

## Numerical precision

**PASS**

The public interface does not expose the full numerical weighting architecture.

The methodology note states that internal weights are design calibrations rather than empirical estimates.

## English-language review

**PASS WITH MINOR FUTURE COPYEDIT OPTION**

The English version is written as standalone academic/policy copy rather than a literal translation of the Russian interface.

The origin of the abbreviation TOS is explained at first use.

## Sources

**PASS**

A compact Research Foundations section is included with academic, legal/institutional, and policy/methodological groups.

The public package intentionally does not reproduce the full bibliography of the academic model.

## GitHub / metadata readiness

**PASS WITH PLACEHOLDERS**

Included:

- `index.html`
- `README.md`
- `CITATION.cff`
- `.nojekyll`
- separated CSS and JavaScript
- OpenGraph title and description metadata
- citation block
- repository button logic

Still required after the repository is created:

1. replace `GITHUB_PAGES_URL_PLACEHOLDER` in `README.md`;
2. set `REPOSITORY_URL` in `assets/js/app.js`;
3. optionally add `og:url`;
4. optionally add an original `og:image` preview;
5. select a reuse license if desired.

## Release decision

**Suitable for public GitHub v1.1 after repository/Pages URLs are inserted.**
