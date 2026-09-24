# RFC 0001 Machine v1.09

Status: ratified_stable  
Audience: AI Loaders, Recorders, agent frameworks

## Required Loader Awareness

A Loader SHOULD identify:

- Format: `AI_TAPE`
- schema version
- schema version authority where present
- tape identity and lineage
- tape class
- capture assessment
- export assessment
- restore-first state
- active asset status where relevant
- capability-floor implications where relevant

## Required Recorder Awareness

A Recorder SHOULD:

- preserve v1.08 export honesty
- emit clean save-ready Markdown when file creation is unavailable
- never claim file/export success unless it occurred
- declare schema authority where version/status ambiguity matters
- identify active assets where relevant
- protect active meaning where required for continuation
- avoid exhaustive asset inventories unless needed
- avoid importing open-territory material into the protected floor

## Schema Version Authority

Minimal operational block:

```yaml
schema_version_authority:
  declared_schema_version: 1.09
  authority_status: ratified_stable
  ratified: true
```

Authority states:

```yaml
authority_states:
  - ratified_stable
  - candidate
  - experimental
  - research
  - deprecated
  - archived
  - local_private
```

## Active Asset Protection

Active asset protection is conditional.

It applies when active assets materially affect continuation, review, verification, reproduction, or safe modification.

An Active Asset is any current project material — artifact, open question, risk, pending decision, or defended stance — that a competent successor would need in order to continue, verify, review, reproduce, or safely modify the work without re-discovery.

Minimal block:

```yaml
active_asset_protection:
  active_assets_present: unknown
  active_assets_checked: no
  asset_status_confidence: unknown
  notes: "No active asset assessment was required for this operational tape."
```

Zero-loss guidance:

```text
Do not drop or paraphrase active assets into non-existence for tidiness, brevity, or aesthetic uniformity.
```

## Capability-Floor Balance

The floor must remain usable across a wide range of model capabilities.

Do not make baseline restoration depend on experimental 14+ structures.

## Exclusions

Do not import v2.0, v2.0S, v2.0Sa, ERP, Liferaft, GODZILLA, or other open-territory material into v1.09.

No Free Baton. No Semantic Density. No relationship maps.
