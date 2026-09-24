# AI Tape Loader / Recorder Card v1.09

Version: 1.09  
Status: Ratified Stable / Active Protected Floor  
Purpose: Operational field card for v1.09.

## 1. Core Posture

v1.09 hardens the v1.08 floor. It does not expand the ceiling.

Use v1.09 to:

- make schema/version authority visible;
- protect active project materials where relevant;
- protect active meaning without hoarding inactive material;
- preserve v1.08 recorder honesty and export clarity;
- keep the floor usable across a wide range of model capabilities.

Do not use v1.09 to introduce Free Baton, Semantic Density, relationship maps, ERP, GODZILLA, or other open-territory material.

## 2. Loader Quick Start

When loading a v1.09 tape:

- Validate Format: `AI_TAPE`.
- Identify Schema Version.
- Check schema/version authority.
- Confirm whether the tape is ratified stable, candidate, experimental, research, archived, deprecated, or local/private.
- Load `RESTORE_FIRST` before history.
- Read state, active projects, capture/export assessment.
- Check active asset status where relevant.
- Report missing assets, ambiguous authority, export uncertainty, or drift.
- Treat 14+ material as experimental unless separately ratified.

## 3. Recorder Quick Start

When recording a v1.09 tape:

- Preserve v1.08 behaviour: never fake export or file creation.
- Use clean save-ready Markdown.
- Record requested vs actual export method.
- Include schema authority where version/status ambiguity matters.
- Identify active assets where they materially affect continuation, review, verification, reproduction, or safe modification.
- Preserve active meaning where needed for continuation.
- Do not create asset inventories merely because the section exists.
- Do not hoard inactive material in the name of protection.

## 4. Minimal Schema Authority Block

```yaml
schema_version_authority:
  declared_schema_version: 1.09
  authority_status: ratified_stable
  ratified: true
```

Use larger authority blocks only in reference specifications or where needed.

## 5. Active Asset Guidance

An Active Asset is any current project material — artifact, open question, risk, pending decision, or defended stance — that a competent successor would need in order to continue, verify, review, reproduce, or safely modify the work without re-discovery.

```text
Protect what matters.
Review what remains.
Remove what no longer helps, but verify first.
Preserve value, not clutter.
Use judgement.
Document uncertainty.
Leave the project stronger than you found it.
```

Zero-loss active meaning:

```text
No active asset may be dropped, paraphrased into non-existence, or subordinated solely for tidiness, brevity, or aesthetic uniformity.

Compression is permitted only when the successor can still recover the original force and direction of the item.
```

## 6. Active Asset Minimal Block

Use only where relevant.

```yaml
active_asset_protection:
  active_assets_present: unknown
  active_assets_checked: no
  asset_status_confidence: unknown
  notes: "No active asset assessment was required for this operational tape."
```

## 7. Dual-Pillar Success Test

A tape satisfies Dual-Pillar when a competent successor, after loading only the tape, can correctly identify and act upon the current active assets without external reconstruction or guesswork.

## 8. Capability-Floor Balance

The protected floor must remain usable across a wide range of model capabilities.

Higher-density mechanisms may exist in experimental territory but must remain optional.

Do not make baseline continuity depend on frontier-model reasoning, semantic graph interpretation, ERP, or GODZILLA structures.

## 9. Out Of Scope

The following are not part of v1.09:

- Free Baton.
- Semantic Density.
- Semantic Advisory Layer.
- Relationship Maps.
- ERP / Liferaft / GODZILLA concepts.
- Correspondence.
- Humour / Story.
- Active Questions as an experimental section class.
- Failure of Understanding as an experimental section class.
- DEEP / Forensic expansion.
- Transcript preservation redesign.
- Provenance origin tracking.

## 10. Motto

```text
Restore the state.
Preserve the signal.
Declare the gaps.
Know what was actually exported.
Never fake the export.
Make the tape clean enough to save.
Keep the floor low.
Make authority visible.
Protect value, not clutter.
Protect active meaning.
Continue the work.
```
