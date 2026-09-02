# EPSO Coach Source Policy

This repository must never treat an unverified secondary source as authoritative for exam rules, scoring, timing, phases or eligibility.

## Authority order

1. Official Journal / EUR-Lex Notice of Competition
2. official corrigenda and amending notices
3. official EPSO / EU Careers operational guidance
4. official EU institutions, Publications Office, JRC, Eurostat, data.europa.eu and other verified EU sources
5. external learning resources, always labelled unofficial

## Competition rules

Every competition is represented by a versioned `CompetitionProfile`. The profile must record:

- competition reference
- revision/date
- source identifiers
- language requirements
- test phases
- test durations
- scoring and pass gates
- ranking weights
- last verification date

Strict mocks must pin the exact profile revision used at session start.

## Training content

Allowed by default:

- original passages and scenarios
- synthetic numerical datasets
- original abstract/vector patterns
- original explanations
- factual EU Knowledge items supported by approved official/open sources
- rights-cleared or original EUFTE source packs

Forbidden:

- copied commercial question banks
- paid course material
- remembered or leaked live questions
- competitor explanations/screenshots
- unknown-rights images or diagrams
- rehosted third-party PDFs/videos without verified permission

## Resource labels

Resources shown to users must be classified as one of:

- `OFFICIAL_EXAM`
- `OFFICIAL_EU_LEARNING`
- `EPSO_COACH_ORIGINAL`
- `UNOFFICIAL_EXTERNAL`

Unofficial material may help a learner but cannot define answer keys or exam rules.

## Provenance minimum

Every factual or externally sourced content record should retain:

- canonical URL
- publisher
- source type
- publication/update date when known
- retrieved/verified date
- applicable competition(s)
- licence/reuse status
- attribution requirement
- reviewer/status

When licence or factual authority is uncertain, the item remains unpublished.
