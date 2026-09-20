# Dual Engine Epistemic Topology

Status: research seed / engineering concept  
Working status: concept captured from exploratory human-LLM discussion. Project name intentionally provisional.

## Core Idea

Build a double-blind interpretive machine in which a human participant and a language model independently interpret the same stimulus without seeing, influencing, or anchoring on the other participant's response. Once both responses are locked, a deterministic comparison layer overlays the two representations and maps their relationship.

The objective is not to decide whether the human or model is better. It is to map where two differently constrained cognitive engines converge, diverge, contradict, omit information, or expose complementary information that the other does not independently recover.

## Research Thesis

Human and language-model interpretation may exhibit stable, measurable topologies of complementary strength, weakness, overlap, conflict, and shared blindness. Repeated double-blind mapping across many stimulus classes could reveal systematic information-processing gaps. Those gaps can become explicit engineering targets for fusion architectures, specialised models, training objectives, interfaces, or additional cognitive components.

## Experimental Primitive

```text
Stimulus S -> Human interpretation H1
Stimulus S -> Model interpretation M1

H1 and M1 are produced in isolation and locked before either participant can
inspect the other.

Deterministic mapper D(H1, M1) -> topology Omega(S)
```

Independence is essential. If either participant sees the other's interpretation before producing its first-pass response, convergence can be caused by anchoring rather than independent cognition.

## Topology to Map

| Region | Meaning | Potential system response |
| --- | --- | --- |
| Convergence | Both independently recover substantially the same information. | Record independent agreement and provenance. |
| Human-unique | Information appears in H1 but not M1. | Preserve human grounding; investigate why the model missed it. |
| Model-unique | Information appears in M1 but not H1. | Surface documentary or representational contribution and evidence basis. |
| Conflict | Both address the same feature but reach incompatible interpretations. | Preserve disagreement and route for further evidence. |
| Different abstraction | Both may be compatible but operate at different conceptual levels. | Map hierarchy rather than misclassifying as contradiction. |
| Uncertainty divergence | Participants assign materially different uncertainty. | Expose the mismatch rather than averaging confidence. |
| Shared blind spot | Neither independently captures information later established as relevant. | Treat as a candidate engineering gap. |

## Why the Gaps Matter

The most interesting output may be neither agreement nor disagreement, but recurrent empty regions. If shared or asymmetric gaps recur across participants, models, domains, and stimulus types, the project can move from descriptive comparison to targeted engineering.

A recurrent gap can be treated as a specification: what information is missing, under what conditions, from which engine, with what downstream consequence, and what additional representation or processing would be required to recover it.

## Engineering Trajectory

1. Characterise the gap rather than assuming its cause.
2. Test whether prompt changes, retrieval, multimodality, memory, or other existing mechanisms close it.
3. If the gap persists, design a specialised component or model specifically against that measured deficit.
4. Run the new component blind against the same stimuli.
5. Overlay its contribution with H and M to determine whether it genuinely occupies previously empty topology or merely duplicates an existing engine.

A future architecture could contain a human engine H, a broad representational model M, one or more gap-specialist components C1 through Cn, and a deterministic provenance-preserving mapper. The taxonomy of roles should emerge from measurements rather than being assumed in advance.

## Second Stage Reciprocal Experiment

After the blind first pass, reveal the mapped topology to both participants and request independent second interpretations. This measures whether each engine can repair its representation after exposure to information supplied by the other.

- **Human gain:** change from H1 to H2 after topology exposure.
- **Model gain:** change from M1 to M2 after topology exposure.
- **Persistent conflict:** disagreement remaining after reciprocal information exposure.
- **Joint residual:** relevant information still absent after both engines receive the overlay.

The joint residual is a particularly strong future architecture target because it may identify information that neither existing engine represents well even after cross-exposure.

## Scaling the Chamber

The initial chamber can be small and methodological. Later runs should expand across many humans, model families, repeated model runs, and deliberately varied stimulus classes. This separates individual topology from more stable between-engine patterns.

Candidate stimulus classes include literal factual prose; ambiguous language and underspecified context; humour, hyperbole, sarcasm, implication, and pragmatic shorthand; social and interpersonal scenarios; bureaucratic, legal, policy, and institutional language; technical and cross-domain material; conflicting or incomplete evidence; deceptive or strategically framed communication; and multimodal or environmentally grounded scenarios where available.

## Measurement Cautions

- Do not encode the desired conclusion that humans are strong at X and models are strong at Y.
- Avoid a free-form third LLM as the authoritative mapper; another mediated inference layer may erase the phenomenon being measured.
- Define a common representation schema and deterministic relation rules before analysing outcomes.
- Preserve raw responses and provenance so mappings can be audited and reprocessed under later schemas.
- Measure within-human, within-model, and between-engine variation before claiming stable engine-level differences.
- Use external reference evidence where possible to distinguish unique insight from unique error and to identify shared blind spots.

## Candidate Internal Representation

A claim-level record could contain: claim; source participant; evidence channel; grounding type; confidence; known limitations; relation to corresponding claims; counterevidence; agreement or conflict class; unresolved gap; and later outcome or reference status.

## Design Principle

Do not eliminate the boundary between human and machine reasoning. Instrument it.

The system should resist collapsing two interpretations into a single authoritative answer too early. The boundary itself contains information: independent convergence, asymmetric coverage, disagreement, uncertainty, and shared absence are all signals.

## Research Programme

1. **The Externalisation Gap:** how lived or private reality is transformed and filtered before entering model-accessible records.
2. **The Unwritten Substrate:** how human meaning depends on pragmatic, embodied, social, and contextual information not fully encoded in literal text.
3. **Asymmetric Epistemic Partnership:** how human and model evidence channels differ, overlap, and complement one another.
4. **Dual-Engine Epistemic Topology:** a double-blind system for independently interpreting stimuli, deterministically mapping the resulting topology, identifying recurrent gaps, and engineering against them.

## Project Naming Problem

This concept has outgrown the informal Leviathan 2.0 label. A future project name should evoke mapping, parallax, stereoscopic reconstruction, complementary viewpoints, or topology without implying that either participant is the authoritative observer. Early naming territory includes Parallax, Stereopsis, Binocular, Atlas, Confluence, Interstice, Toposcope, Janus, Dyad, Crossview, Epistemic Parallax, and Cognitive Parallax.

## One Sentence Formulation

A double-blind human-LLM interpretation chamber deterministically overlays independent cognitive maps to measure convergence, divergence, conflict, and shared blind spots, then uses recurrent topology as an engineering specification for systems that can recover information neither side reliably captures alone.
