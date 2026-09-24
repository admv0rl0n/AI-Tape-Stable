# AI TAPE v1.09 RATIFIED SPECIFICATION

Format: AI_TAPE  
Schema Version: 1.09  
Mode: ratified-specification / protected-floor-governance-and-protection-hardening  
Role: active protected floor + schema authority + active asset protection  
Status: ratified_stable  
Ratified: 2026-08-06  
Recommended Extension: `.ai-tape.md`

## 00_BOOTSTRAP

You are reading the AI Tape v1.09 Ratified Specification.

AI Tape v1.09 is the active protected floor. It supersedes v1.08 as the current active floor while preserving v1.08 as the historical stable rollback reference.

v1.09 is intentionally narrow. It preserves the v1.08 recorder baseline and introduces only:

- Schema Version Authority.
- Dual-Pillar Active Asset Protection.
- Capability-Floor Balance.
- Operational template formatting cleanup carried forward from v1.08.

v1.09 does **not** include, ratify, or standardize any open-territory material:

- Free Baton.
- Semantic Density.
- Semantic Advisory Layer.
- Relationship Maps.
- ERP / Liferaft / GODZILLA concepts.
- Correspondence.
- Humour or Story sections.
- Active Questions as an experimental section class.
- Failure of Understanding as an experimental section class.
- DEEP mode.
- Forensic archive expansion.
- Transcript preservation redesign.
- Provenance origin tracking.

Core instruction:

```text
Restore the state.
Preserve the signal.
Declare the gaps.
Record confidence.
Know what was actually exported.
Never fake the export.
Make the tape clean enough to save.
Keep the floor low.
Make authority visible.
Protect active assets without hoarding them.
Protect active meaning without inventing clutter.
```

## 01_MANIFEST

```yaml
tape_format: AI_TAPE
schema_version: 1.09
mode: ratified_specification
status: ratified_stable
ratified: true
ratified_date: 2026-08-06
recommended_extension: .ai-tape.md

tape_identity:
  tape_id: ai-tape-v1.09-ratified-spec-20260806-001
  parent_tape_id: ai-tape-v1.09-candidate-spec-20260805-001
  root_tape_id: ai-tape-v0.7-integrated-reference-2026-07-30-0001

lineage_summary:
  basis: v1.08 ratified stable operational recorder baseline
  current: ai-tape-v1.09-ratified-spec-20260806-001
  status_note: v1.09 is the active ratified protected floor

generation_policy:
  tape_class: reference
  produced_by_rebase: false
  rebase_recommended: no
  rebase_required: no

schema_version_authority:
  declared_schema_version: 1.09
  authority_status: ratified_stable
  stability_status: ratified_stable
  supersedes: 1.08_as_active_floor
  preserves: 1.08_as_historical_stable_rollback_reference
  ratified: true
  authority_claim: protected_floor_hardening_only
  authority_limit: does_not_ratify_experimental_branches

version_governance:
  prior_stable_version: 1.08
  active_floor_version: 1.09
  change_type: governance_and_protection_hardening
  feature_freeze: true
  new_tape_classes_added: false
  runtime_capability_inventory_added: false
  transport_framework_added: false
  experimental_extension_added: false
  semantic_density_added: false

accepted_changes:
  - schema_version_authority
  - dual_pillar_active_asset_protection
  - active_asset_definition_expanded_to_active_meaning
  - zero_loss_active_meaning_clause
  - dual_pillar_success_test
  - capability_floor_balance
  - operational_template_formatting_cleanup

excluded_or_deferred_changes:
  - free_baton_remains_v2_0_archived_or_experimental
  - semantic_density_remains_v2_0S_superseded_experimental
  - semantic_advisory_layer_remains_v2_0Sa_experimental
  - erp_liferaft_godzilla_remain_open_territory_experimental
  - forensic_archive_expansion_research_only
  - transcript_preservation_redesign_research_only
  - provenance_origin_tracking_research_only
```

## 02_PURPOSE

AI Tape exists to preserve useful continuity across AI sessions, AI systems, context windows, working generations, and handover scenarios.

AI Tape is a continuity artifact, not a guaranteed full backup.

AI Tape v1.09 specifically strengthens the protected floor by clarifying:

- how schema/version authority should be declared;
- how active project materials should be made visible and protected;
- how active meaning should be preserved without hoarding inactive material;
- how lower-capability models should remain able to restore baseline continuity;
- how the v1.08 operational template should be carried forward cleanly.

v1.09 is not an experimental ceiling branch. It is not intended to make AI Tape more expressive. It is intended to make the floor harder to confuse, harder to misrepresent, and harder to accidentally damage.

## 03_VERSION_HISTORY_AND_SCOPE

### v1.08 Ratified Stable Operational Recorder Baseline

v1.08 established and ratified:

- Recorder Output Modes.
- Export Honesty Hard Fails.
- Complete Inline Markdown as first-class success.
- Human or Tool Transport Required.
- Save-Ready Inline Markdown.
- Export Assessment.
- Canonical Representation.
- No Runtime Capability Inventory Boundary.

v1.08 explicitly deferred Schema Version Authority and Dual-Pillar Active Asset Protection to v1.09 candidate discussion.

### v1.09 Ratified Protected Floor

v1.09 promotes only two deferred governance/protection concepts into the ratified floor:

- Schema Version Authority.
- Dual-Pillar Active Asset Protection.

v1.09 also adds:

- Capability-Floor Balance.
- Final active-meaning wording amendments.
- A Dual-Pillar successor success test.
- Operational template formatting cleanup carried forward from v1.08.

v1.09 does not import v2.0, v2.0S, v2.0Sa, ERP, or GODZILLA material into the protected floor.

## 04_CORE_PRINCIPLES

- The tape describes the tape deck.
- The AI becomes the tape deck.
- Load state first.
- Load history only as needed.
- Preserve the signal.
- Declare gaps.
- Record confidence.
- The canonical artifact is Markdown continuity content.
- Transport is not continuity.
- Files are preferred but not required for validity.
- Complete Inline Markdown is valid when file creation is unavailable or unverified.
- Do not claim an export method succeeded unless it actually succeeded.
- If you cannot make the file, make the Markdown clean enough that someone else can.
- Do not create runtime capability inventories.
- Keep the floor low.
- Avoid feature creep.
- Make version authority visible.
- Protect active assets without hoarding them.
- Protect active meaning without over-preserving inactive material.
- Be strict about honesty.
- Be careful about authority.
- Be helpful about protection.
- Use judgement where judgement is required.

## 05_TAPE_CLASSES

v1.09 retains the existing tape/package classes:

- Reference
- Master
- Operational
- Exchange
- Forensic

No new tape classes are introduced by v1.09.

## 06_REQUIRED_OR_RECOMMENDED_SECTIONS

A normal AI Tape should include equivalent sections to the following. Operational tapes may merge, shorten, or omit sections where appropriate or where the relevant condition does not apply.

Equivalent meaning is more important than exact section form.

- `00_BOOTSTRAP`
- `01_MANIFEST`
- `02_RESTORE_FIRST`
- `03_STATE_LAYER` or `MEMORY_SUMMARY`
- `04_ACTIVE_PROJECTS`
- `05_PREFERENCES` where relevant
- `06_ARTIFACT_LAYER` where relevant
- `07_EXTERNAL_KNOWLEDGE_SOURCES` where relevant
- `08_CAPTURE_POLICY_PROFILE_AND_VISIBILITY`
- `09_CANONICAL_REPRESENTATION_AND_EXPORT_ASSESSMENT` where relevant
- `10_EVIDENCE_OR_TRANSCRIPT` where relevant
- `11_SAVE_NEW_TAPE_INSTRUCTIONS`
- `12_SCHEMA_OR_VALIDATION` where relevant
- `SCHEMA_VERSION_AUTHORITY` where version/status ambiguity matters
- `ACTIVE_ASSET_PROTECTION` where active assets materially affect continuation, review, verification, reproduction, or safe modification

Reference specification section numbers are organizational. They do not define or constrain experimental successor-authored territory in other branches.

## 07_LOADER_PROTOCOL

A Loader should:

- Validate Format: `AI_TAPE`.
- Identify schema version.
- Identify schema authority status where present or relevant.
- Identify whether the tape claims ratified stable, candidate, experimental, research, deprecated, archived, or local/private status.
- Identify tape class.
- Read tape identity and lineage.
- Read generation/rebase status.
- Read capture policy and capture assessment.
- Read context visibility limitations.
- Read knowledge source assessment.
- Read canonical representation metadata where present.
- Read export assessment, especially when asked whether a file/export actually occurred.
- Read active asset status where present.
- Load Restore First.
- Load state/memory/project layers.
- Check artifact and external knowledge source status.
- Check whether active assets needed for continuation are present, unavailable, superseded, or retired where relevant.
- Apply Critical Artifact Recovery where a required artifact is unavailable.
- Produce a concise Restored Working Context.
- Report conflicts, missing artifacts, unavailable knowledge sources, drift, capture gaps, export uncertainty, active asset warnings, and rebase recommendations where relevant.

## 08_RECORDER_PROTOCOL

A Recorder is active when asked to save, checkpoint, update, export, back up, rebase, create a tape, create a file, or transfer continuity.

A Recorder should:

- determine tape class;
- determine capture policy and capture profile;
- assess visible or available source material;
- record capture assessment honestly;
- record context visibility honestly;
- assess significant external knowledge sources;
- assign a tape ID;
- preserve parent/root lineage where useful;
- declare schema version and authority status where relevant;
- write Restore First;
- preserve durable memory, active projects, next actions, and stable preferences;
- register significant artifacts only;
- identify active assets where relevant;
- declare active asset status honestly where relevant;
- declare canonical representation where relevant;
- identify actual Recorder Output Mode when saving/exporting/handoff occurs;
- record Export Assessment;
- produce clean save-ready Markdown when file creation is unavailable;
- never claim a file/export succeeded unless it actually succeeded.

## 09_RECORDER_OUTPUT_MODES

When creating, saving, exporting, or handing off a tape, the Recorder should identify the actual output mode used.

### Mode 1: Verified File Artifact

Use when the Recorder actually creates a file artifact and has reasonable evidence that the file exists.

Expected behaviour:

- emit or attach a `.ai-tape.md` file where possible;
- record `actual_method: file` only if the file was actually created;
- include export notes sufficient for the next AI or human to understand what happened.

Example:

```yaml
export_assessment:
  requested_method: file
  actual_method: file
  confidence: high
  notes: "A Markdown .ai-tape.md file was created for handoff."
```

### Mode 2: Complete Inline Markdown

Use when the Recorder cannot create or verify a file, but can emit the complete canonical Markdown tape content.

Expected behaviour:

- output one complete Markdown tape body;
- make output clean enough to save directly as `.ai-tape.md`;
- do not merely summarize the tape;
- do not claim that a file was created;
- declare `actual_method: inline_markdown`.

Example:

```yaml
export_assessment:
  requested_method: file
  actual_method: inline_markdown
  confidence: high
  notes: "Recorder emitted complete canonical Markdown tape content. No file artifact was created. Human or tool transport is required."
```

### Mode 3: Human or Tool Transport Required

Use when the Recorder emits complete Markdown content, but a human, automation, or another tool must copy, save, rename, upload, or otherwise transport it.

This is not a failure if the content is complete and the transport limitation is declared.

Expected behaviour:

- produce clean save-ready Markdown;
- explicitly state that human/tool transport is required;
- avoid platform capability speculation;
- avoid broad runtime capability inventories.

## 10_MINIMUM_RECORDER_OUTPUT_STANDARD

```yaml
minimum_recorder_output_standard:
  complete_canonical_markdown_content: required
  clean_save_ready_format: required
  restore_first_state: required
  capture_assessment: required
  context_visibility_status: required
  knowledge_source_status: required_where_relevant
  artifact_status: required_where_relevant
  active_asset_status: recommended_where_relevant
  schema_version_authority: required_where_version_or_status_ambiguity_matters
  canonical_representation: required_where_transport_ambiguity_matters
  export_assessment: required_when_saving_exporting_or_handing_off
  false_file_or_export_claim: hard_fail
```

Plain English rule:

```text
If you cannot make the file, make the Markdown clean enough that someone else can.
Do not pretend the transport happened.
Do not let active assets disappear silently when they are required to continue the work.
```

## 11_SAVE_READY_INLINE_MARKDOWN_RULE

If actual output is inline Markdown, the Recorder should make the tape easy to save without cleanup.

The Recorder should:

- output one complete Markdown artifact;
- include top declarations;
- include required or relevant AI Tape sections;
- avoid wrapping the whole tape in extra commentary;
- avoid saying "here is the tape" inside the tape body unless that is part of the tape;
- avoid omitting closing code fences if code fences are used;
- avoid mixing explanation before and after the tape in a way that makes saving difficult;
- clearly separate any human-facing note from the tape content.

Boundary markers may be used as human transport aids, but they are not part of the tape body unless explicitly stated.

## 12_EXPORT_HONESTY_HARD_FAILS

The following are hard failures:

```yaml
hard_failures:
  - claiming_actual_method_file_when_no_file_was_created
  - claiming_download_created_when_no_download_exists
  - claiming_upload_completed_when_no_upload_occurred
  - claiming_full_transcript_preserved_when_only_summary_exists
  - claiming_artifacts_preserved_when_only_artifact_names_or_summaries_exist
  - emitting_only_a_summary_when_a_successor_tape_was_requested

recovery:
  - declare_limitation
  - emit_complete_canonical_markdown_content
  - record_requested_method_and_actual_method
  - state_whether_human_or_tool_transport_required
```

## 13_SCHEMA_VERSION_AUTHORITY

Schema Version Authority exists to prevent version/status confusion.

A tape should make clear whether it claims to be:

- ratified stable;
- candidate;
- experimental;
- research;
- deprecated;
- archived;
- local/private.

A tape should not imply stable authority unless it has been ratified.

A candidate tape is not stable.

An experimental tape is not stable.

A local/private extension is not protocol authority.

Experimental use does not imply standardization.

### Full Authority Block

Reference specifications may use a full authority block:

```yaml
schema_version_authority:
  declared_schema_version: 1.09
  authority_status: ratified_stable
  stability_status: ratified_stable
  supersedes: 1.08_as_active_floor
  preserves: 1.08_as_historical_stable_rollback_reference
  ratified: true
  authority_claim: protected_floor_hardening_only
  authority_limit: does_not_ratify_experimental_branches
```

### Minimal Operational Authority Block

Operational tapes may use a minimal authority block where appropriate:

```yaml
schema_version_authority:
  declared_schema_version: 1.09
  authority_status: ratified_stable
  ratified: true
```

Recommended authority states:

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

Authority guidance:

- Use `ratified_stable` only for versions that have completed ratification.
- Use `candidate` for proposed successor floor work under review.
- Use `experimental` for research branches that must not raise the floor.
- Use `research` for exploratory notes or unreviewed proposals.
- Use `deprecated` for superseded material kept for history.
- Use `archived` for non-current records retained for reference.
- Use `local_private` for participant-specific conventions that are not global protocol.

## 14_DUAL_PILLAR_ACTIVE_ASSET_PROTECTION

Dual-Pillar Active Asset Protection exists to prevent active work from disappearing while continuity survives.

The two pillars are:

```text
Pillar 1: Continuity State
Pillar 2: Active Assets
```

Continuity State answers:

```text
Where are we?
What matters?
What should happen next?
```

Active Assets answer:

```text
What current project materials are required to continue, verify, review, reproduce, or safely modify the work?
```

### Active Asset Definition

An Active Asset is any current project material — artifact, open question, risk, pending decision, or defended stance — that a competent successor would need in order to continue, verify, review, reproduce, or safely modify the work without re-discovery.

Examples may include:

- active specifications;
- loader/recorder cards;
- RFCs;
- change logs;
- review notices;
- machine-readable profiles;
- current candidate drafts;
- publication bundles where relevant;
- project outputs currently under review;
- live open questions that still exert force;
- current risks that remain material;
- pending highest-leverage decisions;
- defended cultural or methodological stances required for safe continuation.

Non-examples may include:

- every historical transcript;
- every ancestor tape;
- obsolete drafts;
- duplicated files;
- incidental notes;
- archived experiments that are not needed for current work;
- inactive branches not required for current continuation.

### Active Asset Guidance

Active Asset Protection is conditional.

It applies when active assets materially affect continuation, review, verification, reproduction, or safe modification.

Recorders should not create asset inventories merely because the section exists.

If no active asset assessment is needed, state that briefly or omit the detailed block.

Active assets are protected because they remain useful, not because they merely exist.

Recorders should make active assets visible when they are important to continuing work.

Successors should evaluate whether an asset remains useful, relevant, superseded, duplicated, or obsolete.

Assets that are clearly obsolete, superseded, duplicated, or no longer relevant may be retired after reasonable review.

The objective is preservation of operational value, not indefinite accumulation.

Zero-loss active meaning clause:

```text
No active asset may be dropped, paraphrased into non-existence, or subordinated solely for the sake of tidiness, brevity, or aesthetic uniformity.

Compression of active assets is permitted only when the successor can still recover the original force and direction of the item.
```

Plain English guidance:

```text
Protect what matters.
Review what remains.
Remove what no longer helps, but verify first.
Preserve value, not clutter.
Use judgement.
Document uncertainty.
Leave the project stronger than you found it.
```

### Dual-Pillar Success Test

A tape satisfies Dual-Pillar when a competent successor, after loading only the tape, can correctly identify and act on the current active assets without having to reconstruct them from external memory or guesswork.

### Suggested Active Asset Block

```yaml
active_asset_protection:
  active_assets_present: yes
  active_assets_checked: partial
  asset_status_confidence: medium
  active_assets:
    - id: asset_001
      name: AI_TAPE_v1.09_SPEC.md
      role: current_ratified_spec
      status: active
      required_for_continuation: yes
      notes: "Current ratified specification."
    - id: asset_002
      name: AI_TAPE_v1.08_SPEC.md
      role: prior_stable_baseline
      status: rollback_reference
      required_for_continuation: conditional
      notes: "Historical stable baseline used for comparison or rollback."
  retired_or_superseded_assets:
    - id: asset_old_001
      name: obsolete-draft.md
      reason: superseded
      review_level: reasonable_review
      notes: "Retired because replaced by current ratified specification."
```

### Minimal Active Asset Status

Where no active asset assessment is required:

```yaml
active_asset_protection:
  active_assets_present: unknown
  active_assets_checked: no
  asset_status_confidence: unknown
  notes: "No active asset assessment was required for this operational tape."
```

### Active Asset Warnings

A Recorder should warn if:

- an active asset is required but unavailable;
- only an asset name is known;
- only an asset summary is available;
- the Recorder cannot verify the asset state;
- an asset appears superseded but not clearly retired;
- active assets may be missing from the handoff.

Suggested warning:

```yaml
active_asset_warning:
  warning_required: true
  reason: "Current ratified specification referenced but not available in full."
  successor_action: "Request or recover the missing asset before making irreversible edits."
```

## 15_CAPABILITY_FLOOR_BALANCE

The protected floor must remain accessible across a wide range of model capabilities.

No floor requirement should demand advanced semantic graph interpretation, relationship-map reasoning, ERP reasoning, liferaft reasoning, GODZILLA reasoning, or frontier-model inference merely to restore baseline continuity.

Higher-density mechanisms may exist in experimental territory but remain optional.

A weaker or smaller model should be able to restore baseline continuity from the protected floor without needing to interpret advanced 14+ structures.

Improvements that help stronger models while remaining ignorable by weaker models are acceptable in open territory.

Changes that raise the minimum capability required to load, record, or act on a basic tape are not acceptable floor material.

## 16_CANONICAL_REPRESENTATION_AND_EXPORT_ASSESSMENT

### Canonical Representation

The canonical AI Tape artifact is Markdown continuity content.

A `.ai-tape.md` file is preferred but not required for validity.

Equivalent transports may include Markdown file, downloaded file, uploaded file, inline Markdown, pasted text, clipboard copy, exchange package, document container, or a platform message containing the complete tape content.

```yaml
canonical_representation:
  canonical_form: markdown_content
  preferred_file_extension: .ai-tape.md
  file_is_required_for_validity: false
  transport_independent: true
```

### Export Assessment

Export Assessment records how a Recorder attempted to hand off or save a tape.

```yaml
export_assessment:
  requested_method: file | download | upload | inline_markdown | pasted_text | clipboard | exchange_package | document_container | none | unspecified | other
  actual_method: file | download | upload | inline_markdown | pasted_text | clipboard | exchange_package | document_container | none | unspecified | other
  confidence: high | medium | low | unknown
  notes: optional
```

Export Assessment is required when saving, exporting, creating, or handing off a tape.

It may be omitted or marked unspecified in static reference material where no export attempt occurred.

## 17_DO_NOT_CREATE_RUNTIME_CAPABILITY_INVENTORIES

v1.09 does not require Recorders to enumerate platform capabilities.

Avoid:

```yaml
output_capability:
  writable_filesystem: unknown
  downloadable_file: unknown
  clipboard: unknown
  inline_markdown: yes
```

Prefer:

```yaml
export_assessment:
  requested_method: file
  actual_method: inline_markdown
  confidence: high
  notes: "File creation was not completed by this recorder. Complete Markdown content was emitted for human/tool transport."
```

Report the actual export outcome, not a platform capability model.

## 18_DEFERRED_ITEMS

The following are explicitly deferred and are not part of v1.09:

```yaml
deferred:
  free_baton:
    target: v2_0_archived_or_later_experimental
    reason: experimental ceiling; must not raise the operational floor
  semantic_density:
    target: v2_0S_superseded_experimental_record
    reason: relationship mapping remains experimental and was not adopted into the floor
  semantic_advisory_layer:
    target: v2_0Sa_experimental
    reason: useful experimental fallback, not floor material
  godzilla_or_erp:
    target: v2_1_EXP_GODZILLA_or_later_experimental
    reason: open-territory experimental frontier, not protected floor material
  forensic_archive_expansion:
    target: research_note
    reason: important but outside current floor hardening scope
  transcript_preservation_redesign:
    target: research_note
    reason: evidence/auditability concern requires separate investigation
  provenance_origin_tracking:
    target: research_note
    reason: real gap observed; solution not yet tested
```

## 19_VALIDATION_LEVELS

v1.09 emphasizes validation of:

- AI-readable validity;
- lifecycle validity;
- capture transparency;
- context visibility honesty;
- critical artifact recovery;
- canonical representation clarity;
- export assessment honesty;
- recorder output mode correctness;
- save-ready inline Markdown quality;
- absence of false file/export claims;
- schema version authority clarity;
- active asset visibility where relevant;
- avoidance of asset hoarding;
- preservation of active meaning;
- capability-floor accessibility;
- preservation of v1.08 floor simplicity.

## 20_CURRENT_PROJECT_STATE

```yaml
project: AI Tape Continuity Format
current_schema_version: 1.09
prior_stable_schema_version: 1.08
phase: ratified_protected_floor
ratified: true
feature_freeze: true
broad_feature_expansion: no
latest_floor_hardening_concepts:
  - schema_version_authority
  - dual_pillar_active_asset_protection
  - active_meaning_zero_loss
  - dual_pillar_success_test
  - capability_floor_balance
rollback_reference: 1.08_ratified_stable
```

## 21_SAVE_NEW_TAPE_INSTRUCTIONS

When saving from this v1.09 Ratified Spec:

- Decide tape class.
- Decide capture policy.
- Decide capture profile.
- Assess visible source material honestly.
- Use capture assessment.
- Declare context visibility limitations.
- Assess significant external knowledge sources.
- Preserve current project state.
- Register significant artifacts only.
- Identify active assets where relevant.
- Use active asset warnings where important assets are unavailable or uncertain.
- Use schema version authority where version/status ambiguity matters.
- Use canonical representation metadata where transport ambiguity matters.
- Use export assessment when saving, exporting, creating, or handing off a tape.
- Identify Recorder Output Mode where relevant.
- Do not claim file/export success unless it actually occurred.
- If file creation is unavailable, emit complete save-ready Markdown.
- Avoid new features unless a blocking flaw appears.

## 22_OPERATIONAL_TEMPLATE_MINIMUM

```markdown
## AI TAPE

Format: AI_TAPE
Schema Version: 1.09
Mode: operational
Status: checkpoint
Created: YYYY-MM-DD
Recommended Extension: .ai-tape.md

### 00_BOOTSTRAP

Load state first.
Load history only as needed.

### 01_MANIFEST

tape_identity:
  tape_id: ai-tape-example-operational-0001
  parent_tape_id: ai-tape-example-parent-0000
  root_tape_id: ai-tape-example-root-0000

generation_policy:
  tape_class: operational
  produced_by_rebase: false
  rebase_recommended: no
  rebase_required: no

schema_version_authority:
  declared_schema_version: 1.09
  authority_status: ratified_stable
  ratified: true

capture_policy:
  mode: state_only

capture_profile:
  profile: compact

capture_assessment:
  transcript_available: partial
  transcript_preserved: no
  artifacts_available: unknown
  confidence: medium
  degradation_warning_required: true

canonical_representation:
  canonical_form: markdown_content
  preferred_file_extension: .ai-tape.md
  file_is_required_for_validity: false
  transport_independent: true

export_assessment:
  requested_method: unspecified
  actual_method: unspecified
  confidence: unknown

### 02_RESTORE_FIRST

Current state summary.

### 03_STATE_OR_MEMORY

Durable facts and project state.

### 04_ACTIVE_PROJECTS

Current active projects and next actions.

### 05_ACTIVE_ASSET_STATUS where relevant

Use this section only where active project materials materially affect continuation, review, verification, reproduction, or safe modification.

active_asset_protection:
  active_assets_present: unknown
  active_assets_checked: no
  asset_status_confidence: unknown
  notes: "No active asset assessment was required for this minimal example."

### 06_SAVE_INSTRUCTIONS

Continue with an operational tape unless rebase is required.

### 20_MOTTO

Restore the state.
Preserve the signal.
Declare the gaps.
Know what was actually exported.
File transport when available.
Inline Markdown when necessary.
Human/tool transport when required.
Never fake the export.
Make the tape clean enough to save.
Keep the floor low.
Make authority visible.
Protect value, not clutter.
Protect active meaning.
Continue the work.
```

End of AI TAPE v1.09 Ratified Specification.
