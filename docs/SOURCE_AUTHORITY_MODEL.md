# Source Authority Model

This model helps reviewers describe where a candidate item came from. It is simple on purpose and can be refined later.

## Tiers

| Tier | Description | Public Handling |
| --- | --- | --- |
| Official/public institutional source | Public material from an official government, institutional, standards, or recognized public body source. | May be referenced if rights and safety allow. Still requires review. |
| Academic/research source | Papers, research datasets, academic publications, or university materials. | Check license, citation, and scope before use. |
| Published reference source | Dictionaries, books, manuals, public reports, or reference sites. | Check copyright, citation, and allowed use. |
| Community/native-speaker note | Notes from Lao speakers, community reviewers, or domain contributors. | Useful for wording and local context, but should be marked as reviewer/community input. |
| AI-generated candidate | Output from an AI model or AI-assisted tool. | Never automatically trusted. Must be reviewed and source-checked if it contains factual claims. |
| Unknown/unverified source | Source is unclear, missing, or not yet checked. | Do not treat as trusted. Keep as candidate or reject. |

## Core Rule

AI-generated candidate data is never automatically trusted. Fluency is not evidence. A clear Lao sentence can still be wrong, unsourced, unsafe, or unsuitable for public acceptance.

## Suggested Metadata

- source_type
- source_reference
- source_rights_status
- reviewer_note
- review_status
- uncertainty_note
- accepted_for_public_use
