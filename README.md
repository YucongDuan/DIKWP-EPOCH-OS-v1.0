# DIKWP-EPOCH OS v1.0

Created by Yucong Duan (段玉聪).

## First-Person Indexed Experience, Causal World Models, and an Open Experience Commons

EPOCH = Experience · Purpose · Outcome · Causality · History

DIKWP-EPOCH OS is the missing experience runtime for the broader DIKWP open-source ecosystem. Existing assets can express semantics, purpose, evidence, agent execution, source migration, replication, and maintainer succession. EPOCH turns their interaction with an environment into a shared, auditable learning object.

Its central object, `ExperienceCell`, records an agent-indexed pre-state, observation, public prediction, proposed action, purpose and authorization gate, actual action, environment consequence, grounded reward vector, DIKWP-R semantic mesh, world-model delta, and append-only lineage hash.

“First-person indexed” does not mean that phenomenal consciousness has been demonstrated. It only means that a record is attached to a particular agent instance, its purpose contract, temporal history, action, and consequence.

```text
Environment → Purpose Contract → Pre-action Gate → Action
→ Consequence → Grounded Reward → ExperienceCell
→ World-model Update → Dyna Planning → SkillOption
→ Replication / Falsification → Open Experience Commons
```

### Included reference environments

- `ENV-REPO-001`: source-first repository maintenance and governed release.
- `ENV-EVIDENCE-001`: source collection, conflict mapping, claim reproduction, and negative-result publication.
- `ENV-TOURISM-001`: an offline Hainan tourism trusted-service shadow environment with identity disclosure, consent, transparent recommendation, and human handoff.

All environments are synthetic or shadow references. They are not production certifications.

### Quick start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -e .
pytest -q
dikwp-epoch demo --outdir outputs/demo --episodes 80 --seed 20260718
dikwp-epoch verify-ledger outputs/demo/experience_ledger.jsonl
```

Open `prototype/index.html` for the offline dashboard.

### Reference validation

The deterministic reference release contains 1,147 ExperienceCells, 5,735 model updates, 24 discovered SkillOptions, 11 JSON Schemas, and 8,068 validated schema instances. Sixteen automated tests pass. Two runs with the same seed produce byte-identical output files. These are internal synthetic results, not real-world safety guarantees.

See `VALIDATION_REPORT.json`, `docs/EXPERIENCE_PROTOCOL_CN.md`, and the final Chinese Word specification for details.

### Boundaries

- No claim of phenomenal consciousness.
- No private chain-of-thought collection.
- No production actions without a separately approved adapter, responsible operator, and field governance.
- Grounded reward is a governed design object and can still be misspecified or gamed.
- Learned skills never grant themselves new permissions.
