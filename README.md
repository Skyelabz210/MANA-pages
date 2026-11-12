# MANA historical showcase

## CRAM architecture and proof scope (2026-11-12)

Current design intent is residue-space division and an exact magnitude gauge,
with K derived on demand at each winding from authentic phase-locked residue and
anchor state. K is not a persistent scalar payload. Garner reconstruction and
mixed-radix synthetic emission are retired from residue compute; reconstruction
itself is permitted under an explicit operation contract. CRAM transduction
supports heterogeneous operations across phase-locked CRT trays and the
role-aware safe basis. Do not silently replace this architecture with a serial
scalar reconstruction path.

The owner's O(1) magnitude-gauge claim is an intended capability. Any verification
claim must identify the operation, representation, range, cost model and actual
implementation evidence. These historical files do not by themselves prove that
claim or current CRAM conformance.

See the [shared intent and proof-scope record](https://github.com/Skyelabz210/qmnf-lean-coq-security-proofs/blob/main/docs/CRAM_INTENT_AND_PROOF_SCOPE.md) and the
[current integration contract](https://github.com/Skyelabz210/NINE65_v7/blob/main/docs/CRAM_INTEGRATION_CONTRACT.md). Historical results below retain
their original scope; compiling a proof file does not discharge its assumptions
or establish implementation conformance.

## Published snapshot

The bundled source and benchmarks are the January 2026 snapshot, not a current
CRAM conformance release. Its deep-circuit figures refer to the trusted/symmetric
route documented in MANA-definitive. The public evaluator has separate limits.
See [the historical mode distinction](https://github.com/Skyelabz210/MANA-definitive/blob/02d00576eca6a7ac8f8e38851f604f3855fc6e4b/docs/SECURITY_PROOFS.md#L9-L23)
and the shared proof-scope record before interpreting the showcase's claims.
