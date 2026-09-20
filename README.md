# Project Mímir

Project Mímir is a public research-specification repository for a
provenance-preserving, double-blind epistemic cartography system.

It asks how independently produced human and language-model interpretations of
the same stimulus can be compared without premature anchoring, then mapped for
convergence, asymmetry, conflict, uncertainty divergence, and shared blind
spots.

The project name remains provisional. The research programme is the durable
object of this repository.

## Core Idea

The first-pass human and model responses are produced independently and locked
before either side sees the other. A deterministic mapping layer then overlays
the responses rather than collapsing them into a single authoritative answer.

```text
stimulus
  -> independent human interpretation
  -> independent model interpretation
  -> locked, provenance-preserving comparison
  -> topology of agreement, difference, conflict, uncertainty, and absence
```

Recurring gaps can become explicit engineering targets. They may motivate a
retrieval method, representation change, specialist component, interface, or
other bounded intervention, but only after the gap is measured rather than
assumed.

## Relationship to Project Leviathan

Mímir and [Project Leviathan](https://github.com/instance001/project-leviathan)
address complementary layers of the same research problem.

- Mímir improves and audits the available information map.
- Leviathan traverses, transforms, compares, and tests structures represented
  on that map.

Together, the proposed loop is:

```text
map independent interpretations
-> preserve gaps and provenance
-> route justified enrichment where needed
-> apply bounded Leviathan reasoning
-> test reasoning against the map and evidence
-> preserve residual uncertainty or remap
```

Neither project treats novelty, verbosity, agreement, or a single confidence
score as proof. Unsupported bridges, unresolved gaps, and conflicting evidence
must remain inspectable.

## Documents

### Dual Engine Epistemic Topology

Files: `dual_engine_epistemic_topology_research_seed.md` and
`dual_engine_epistemic_topology_research_seed.docx`

Defines the double-blind human-model interpretation chamber, a deterministic
topology mapper, candidate map regions, measurement cautions, and a research
programme for turning recurrent epistemic gaps into testable engineering
specifications.

### Leviathan Epistemic Cartography Integration

Files: `leviathan_epistemic_cartography_integration_seed.md` and
`leviathan_epistemic_cartography_integration_seed.docx`

Defines the proposed integration with Project Leviathan: cartography produces a
richer, provenance-preserving representation; Leviathan performs mechanical
abstraction over it; results are returned for evidence and topology checking.

## Suggested Reading Order

1. `dual_engine_epistemic_topology_research_seed.md`
2. `leviathan_epistemic_cartography_integration_seed.md`

## Repository Boundary

This is a document-only research repository. It does not include a deployed
service, a trained model, participant data, datasets, or an implementation of
the proposed chamber.

Any future experiment or implementation should preserve the core constraints:
independent first-pass interpretation, provenance, pre-specified comparison
rules, auditability, explicit uncertainty, and empirical rather than assumed
component roles.

## License

Project Mímir is released under the GNU Affero General Public License version
3.0. See `LICENSE`.

## Status

Working research seeds. These documents are intended for public study,
critique, citation, derivative research, and AGPLv3-compatible implementation
work.
