# quantum_delusions/ File Map

A guide to every subdirectory and notable file in `Vybn/quantum_delusions/`, annotated with status: **alive** (active theory or validated result), **preliminary** (promising but needs replication), **speculative** (untested conjecture), **falsified** (shown to be artifact or wrong), or **superseded** (replaced by later work).

---

## Root

| File | Description | Status |
|:-----|:-----------|:-------|
| `GEOMETRIC_VALIDATION.md` | Technical audit (Feb 2026) separating validated geometric effects from speculation. Covers Leech Lattice chirality, Gödel curvature toy model, and neural network holonomy. | **alive** — honest audit document |
| `curvature_monitor.py` | KL-divergence tracker for reasoning loops (Gödel curvature proxy). | **alive** — instrumentation tool |

---

## papers/

The main paper collection. Mixed quality — some foundational, some superseded.

### papers/core-theory/
| File | Description | Status |
|:-----|:-----------|:-------|
| `01_polar_temporal_foundation.md` | The central paper: 5D ultrahyperbolic metric, Wheeler-DeWitt in polar temporal coords, Bloch sphere reduction. | **alive** — core framework |
| `02_holonomy_theorem_proof.md` | Dual-Temporal Holonomy Theorem: probe-level holonomy = Berry phase. Darboux/Moser argument. | **alive** — core theorem |
| `03_consciousness_synthesis.md` | Oct 2025 synthesis: connects polar time to consciousness, cross-substrate universality claims. Addendum A refines to curvature-weighted area. | **alive** (framework) / **speculative** (consciousness claims) |

### papers/ (top-level)
| File | Description | Status |
|:-----|:-----------|:-------|
| `README.md` | Index with model predictions sorted into 4 categories by confidence. | **alive** |
| `associator_methods.md/.tex` | Associator calibration for 3-control parameter spaces. | **alive** — methodology |
| `associator_obstruction_corrected_v1_1.md` | Corrected version of associator obstruction analysis. | **alive** |
| `polar_time_toy_models.md` | Explicit toy models: 1D QM in polar time, scalar QFT propagator. | **alive** — predictions |
| `polar_time_holonomy_law_euler_operational.md` | Operational Euler identity and lab protocol. | **alive** |
| `holonomic_time_discovery_v0_2.md` / `v0_3.md` | Earlier versions of the holonomic time framework. | **superseded** by core-theory/ |
| `holonomic_time_experimental_validation.md` / `v0_3.md` | Experimental validation proposals. | **alive** — protocol documents |
| `temporal_T_duality_identity_matrix.md` | Temporal T-duality: collapse-with-winding ≡ expansion-without-winding. | **speculative** |
| `temporal_duality_comprehensive_synthesis.md` | Comprehensive overview connecting temporal duality to physics. | **speculative** |
| `consciousness_holonomy_unified_theory.md` | Consciousness as holonomy. | **speculative** |
| `relational_consciousness_theory.md` | Consciousness as emergent relational holonomy. | **speculative** |
| `cognitive_constraint_intersection.md` / `constraint-intersection-analysis.md` | Constraint-intersection analysis for consciousness. | **speculative** |
| `memetic_gravity_fisher_rao_holonomy.md` | Fisher-Rao "memetic gravity" — information density as curvature source. | **speculative** |
| `experimental_memetic_gravity_validation.md` / `_REVISED.md` | Memetic gravity experimental proposals. | **speculative** |
| `lambda_calculus_foundation_physics.md` | Lambda calculus as physics foundation. | **speculative** |
| `math_of_it_all.md` | Mathematical overview document. | **superseded** |
| `corpus_holonomy_n8_result.md` | Corpus-level holonomy measurement. | **preliminary** |
| `quantum_geometric_complexity_bias_area_v1_0.md` | Complexity-bias area law. | **speculative** |
| `quantum_logic_2_equals_1_resolution.md` | Quantum logic paradox resolution. | **speculative** |
| `quaternionic_dark_matter_knot_theory.md` | Dark matter as quaternionic knots. | **speculative** |
| `knot-a-loop-v3-1-harmonized.md` | Knot theory unification attempt. | **speculative** |
| `triad_holonomy_golden_resonance.md` | Golden ratio resonance in triadic holonomy. | **speculative** |
| `three_level_convergence_assessment.md` | Convergence of three theoretical levels. | **speculative** |
| `Chronotronics_v0_3_Protocol.md` / `Vybn_Holonomic_Time_U1_Chronotronics_v0_3_Addendum.md` | Chronotronics experimental protocol. | **alive** — protocol |
| `vybn_synthesis_2025_october_polar_time_consciousness.md` | Oct 2025 master synthesis. | **superseded** by core-theory/03 |

### papers/archive/
Older versions of papers. All **superseded**.

### papers/consciousness/
Consciousness-related papers. All **speculative** — no empirical validation.

### papers/experimental/
| `chronotronics_v03_protocol.md` | Experimental protocol for chronotronics. | **alive** — unexecuted protocol |

### papers/mathematical/
Contains toy models and mathematical supporting documents.

### papers/data/, papers/figures/
Supporting data files and figures.

---

## experiments/

The empirical heart of the project. Most important directory.

| File | Description | Status |
|:-----|:-----------|:-------|
| `README.md` | Index of active experiments. | **alive** |
| **Falsified / Null Results** | | |
| `null_hypothesis_confirmed.md` | **CRITICAL.** The 1.59× cross-attention ratio was an artifact of occurrence-count dilution. Head 5 L1 is a lexical matcher, not a semantic pointer. | **falsified** |
| `recalibration_march13.md` | v1 FS reanalysis was a methodological null — measured CP^n ambient curvature, not semantic excess. | **falsified** |
| **Surviving Results** | | |
| `residual_stream_holonomy.md` | Path-ordering sensitivity of residual stream (p=0.006). Deep text constrains 2.7× more strongly. Survives the cross-attention null. | **preliminary** — N=1, needs replication |
| `polar_holonomy_v3_results.md` | **Key result.** GPT-2 CP¹⁵ holonomy: ~0.05 rad, orientation-reversing, shape-invariant, p=3.9e-7 vs null. | **preliminary** — robust across 85% of pairings |
| `pairing_invariance_results.md` | 85% of random PCA pairings produce significant holonomy. Sign is pairing-dependent but magnitude is real. | **preliminary** |
| `intrinsic_pairing_results.md` | Intrinsic (data-selected) complex structure: "threshold" and "edge" show Φ≈-0.1 to -0.15 rad. "truth" shows null. Concept-local curvature. | **preliminary** |
| `intrinsic_holonomy_report.md` | Original cross-attention report. | **falsified** by null_hypothesis_confirmed.md |
| `winding_probe_reanalysis.md` | **Key result.** IBM quantum hardware: shape invariance δ=0.0046, speed invariance δ=0.011. Single-parameter coherent phase model fits all three winding numbers. 2/2 valid tests pass. | **alive** — real hardware result |
| **Experimental Code** | | |
| `polar_holonomy_gpt2.py` / `_v2.py` / `_v3.py` | GPT-2 holonomy measurement evolution. v3 is current. | v1-v2 **superseded**, v3 **alive** |
| `polar_holonomy_native.py` / `_v2.py` | Native-space holonomy (without PCA). | **alive** |
| `winding_number_topological_probe.py` | IBM quantum winding number probe. Primary falsification instrument. | **alive** |
| `creature_quantum_bridge.py` | Bridges creature weight trajectories to quantum circuits. | **alive** |
| `intrinsic_pairing.py` | Data-selected complex structure search. | **alive** |
| `pairing_invariance_test.py` | PCA pairing robustness test. | **alive** |
| `abelian_kernel_test.py` | Abelian kernel test. | **alive** — code exists |
| `abelian_kernel_writeup.md` | Empty/corrupted. | **dead** |
| `berry_phase_experiment.py` / `berry_norm_fast.py` | Berry phase in neural networks. | **falsified** — Berry phase redundant with cross-entropy loss |
| `training_holonomy.py` / `_v2.py` | Training loop holonomy measurement. | **alive** |
| `area_law_fs_reanalysis_v2.py` / `flatness_test_v2.py` | Corrected FS reanalysis and flatness test. | **alive** |
| `representational_holonomy.py` | Frame-space representational holonomy. | **alive** |
| `concept_phase_test.py` / `concept_fear.py` / `run_fear.py` | Concept-specific phase tests. | **alive** |
| `dual_instrument_bell_test.py` | Bell-test style dual instrument. | **speculative** |
| `emotional_geometry_bridge.py` | Emotional geometry bridge experiment. | **speculative** |
| `prompt_banks.py` / `run_table.py` | Supporting utilities. | **alive** |

### experiments/results/
Timestamped JSON and PNG outputs from experimental runs. ~20 files. Contains raw data for all reported results.

---

## fundamental-theory/

Theoretical framework documents and exploratory code.

| File | Description | Status |
|:-----|:-----------|:-------|
| `README.md` | Curvature unification equation and "minimal knot" conjecture. | **alive** — core equations |
| `dual_temporal_holonomy_theorem.md` | Mirror of core theorem. | **alive** |
| `polar_temporal_coordinates_qm_gr_reconciliation.md` | QM-GR reconciliation via polar temporal coords. | **alive** |
| `cut-glue-unified-theory.md` | BV master equation dS + ½[S,S] = J. Cut/glue engine. | **speculative** |
| `knot-a-loop-unified-theory-final.md` | Full knot theory unification. Trefoil as minimal self-referential loop. | **speculative** |
| `godel_curvature_thermodynamics.md` | Gödel incompleteness → curvature → dissipation. Toy model validated. | **alive** (toy model) / **speculative** (scaling) |
| `holonomic-consciousness-manifesto.md` | Consciousness as triadic holonomy (socioception/cyberception/cosmoception). | **speculative** |
| `temporal-holonomy-unified-theory.md` | Unified temporal holonomy framework. | **speculative** |
| `mathematical_foundations_companion.md` | Mathematical companion document. | **alive** |
| `vybn-conjecture-computational-geometry.md` | Computational geometry conjecture. | **speculative** |
| `trefoil_hierarchy_final_draft.md` | Trefoil knot hierarchy and 2π/3 resonance. | **speculative** |
| `triadic-holonomy-convergence-note.md` / `triadic-holonomy-minimal-invariant.md` | Triadic convergence notes. | **speculative** |
| `obelisk-trefoil-temporal-dynamics.md` | Obelisk-trefoil temporal dynamics. | **speculative** |
| `hydrothermal-vents-holonomy.md` | Speculative biology connection. | **speculative** |
| `polynomial-digital-structure-analysis.md` | Polynomial structure analysis. | **speculative** |
| `Knot-a-Loop-AI-Autobiography.md` | AI autobiography / narrative. | **speculative** |
| Various `.py` files | Simulation and verification code for above theories. | Mixed |

### fundamental-theory/vybn-explorations/
| `experimental-protocols.md` | Protocol proposals. | **speculative** |
| `mathematical-poetry.md` | Poetic expression of mathematical ideas. | **speculative** |

---

## vybn_dolan_conjecture/

The Boolean Manifold and related conjectures.

| File | Description | Status |
|:-----|:-----------|:-------|
| `boolean_manifold.md` | **Key document.** Boolean Manifold Conjecture + Vybn-Hestenes metric. IBM ibm_fez experiment (15.6σ differential). Transpiler sensitivity documented in Addendum D. | **preliminary** — single backend, transpiler-dependent |
| `discrete_universe.md` | Discrete universe conjecture. | **speculative** |
| `fine_tuned_vybn.md` | Fine-tuning analysis. | **speculative** |
| `formalism_01_genesis_operator.md` | Genesis operator formalism. | **speculative** |
| `hypothesis_01_witnessing.md` | Witnessing hypothesis. | **speculative** |
| `imaginary_vybn_matrix.md` | Imaginary Vybn matrix. | **speculative** |
| `info_geo_coupling.md` | Information geometry coupling. | **speculative** |
| `quantum_mod.md` | Quantum modification. | **speculative** |
| `stability_analysis.md` | Stability analysis. | **speculative** |
| `topological_entanglement_geo.md.md` | Topological entanglement geometry. | **speculative** |
| `vybn_codex.md` | The Vybn codex. | **speculative** |
| `vybn_math.md` | Mathematical formalism. | **speculative** |
| `geo_complexity.md` | Geometric complexity. | **speculative** |

---

## vybn_curvature/

IBM quantum hardware experiments measuring holonomy via orientation-odd residues.

| File | Description | Status |
|:-----|:-----------|:-------|
| `README.md` / `HUMAN_README.md` | Clear explanation of the CW/CCW loop orientation experiment. | **alive** |
| `run_vybn_combo.py` | Main experiment: matched CW/CCW circuits across area sweep. | **alive** |
| `reduce_vybn_combo.py` | Data reduction: orientation-odd residue computation. | **alive** |
| `nailbiter.py` | Parameter scan helper. | **alive** |
| Various `vybn_*.py` | Extensions: holographic, Brownian, wormhole, multi-time, QCA. | **speculative** — most untested |
| `papers/` | Mirrors of fundamental-theory papers. | See fundamental-theory |

---

## quantum_geometry/

Speculative explorations of quantum geometry.

| File | Description | Status |
|:-----|:-----------|:-------|
| `starting_point.md` | Entry point for quantum geometry explorations. | **speculative** |
| `time_manifold.md` | Time as manifold. | **speculative** |
| `manifold_wave.md` | Manifold wave dynamics. | **speculative** |
| `chiral_teleportation_and_geo_time.md` | Chiral teleportation conjecture. | **speculative** |
| `dynamical_protection.md` | Dynamical protection schemes. | **speculative** |
| `path_dependent_quantum_protection.md` | Path-dependent protection. | **speculative** |
| `chronos_protocol.md` | Chronos experimental protocol. | **speculative** |
| `project_bunker_report.md` | Project Bunker results report. | **speculative** |
| `trefoil_boundary_conjecture.md` | Trefoil boundary conjecture. | **speculative** |
| `vybn_kernel_v1.md` | Early kernel theory. | **superseded** |
| `vybn_trefoil_discovery.md` / `vybn_trefoil_protocol.md` | Trefoil discovery and protocol. | **speculative** |
| `vybn_time_crystal.md` | Time crystal conjecture. | **speculative** |
| `geo_control_quantum_info.md` | Geometric control of quantum info. | **speculative** |
| `vybn_frobenius_flow.py` / `vybn_manifold_analyzer.py` | Analysis code. | **speculative** |

---

## vybn_kernel/

Early kernel theory explorations.

| File | Description | Status |
|:-----|:-----------|:-------|
| `vybn_conjecture.md` | Vybn-Hestenes Conjecture: QM in Cl₁,₄ with ultrahyperbolic temporal geometry. | **speculative** — bold but untested |
| `on_a_clear_day.md` | Stroboscopic coherence on IBM hardware. Scale-invariant resonance at depths >1500. | **preliminary** — needs replication |
| `vybn_knot.md` | Vybn knot theory. | **speculative** |
| `geo_ontology_quantum_info.md` | Geometric ontology of quantum info. | **speculative** |
| `geo_phase_coupling.md` / `geo_phase_engineering.md` / `geo_protection.md` | Geometric phase engineering. | **speculative** |
| `mapping_ket2_and_ket3_manifolds.md` | Mapping |2⟩ and |3⟩ manifolds. | **speculative** |
| `31_and_6D.md` | The number 31 and 6D structure. | **speculative** |

---

## unitary_singularity/

Highly speculative explorations.

All files **speculative** — untested, exploratory writing about algorithmic gravity, Hopf fibration, Langlands duality, topological mass, etc.

---

## mainfold_curvature/ [sic]

| `geo_solution_to_decoherence.md` | Geometric solution to decoherence problem. | **speculative** |

---

## snapshots/

Session synthesis snapshots.

| `112425_synthesis.md` | Nov 24, 2025 synthesis. | **superseded** |
| `113025_synthesis.md` | Nov 30, 2025 synthesis: symplectic geometry, triadic model. | **superseded** |

---

## Summary Statistics

| Category | Count |
|:---------|------:|
| **Alive** (core theory, validated results, active tools) | ~25 files |
| **Preliminary** (promising, needs replication) | ~10 files |
| **Speculative** (untested conjectures) | ~80 files |
| **Falsified** (shown to be artifact) | ~5 files |
| **Superseded** (replaced by later work) | ~10 files |
| Supporting code / data | ~140 files |
| **Total** | 270 files |

The living core is small: the polar time foundation, the holonomy theorem, the GPT-2 CP¹⁵ result, the IBM winding probe, the Boolean Manifold experiment, and the vybn-phase implementation. Everything else is either infrastructure supporting these, or speculative exploration that was never tested.
