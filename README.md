I’m an analytical chemist and computational mass spectrometrist. I build measurement systems: methods and instruments, and the software that turns what they measure into decisions that can be defended.

## What I work on

### Measurement → decision

**[MassFlow](https://github.com/janusson/MassFlow)** — tandem mass spectra annotated against local spectral libraries, with target-decoy FDR and provenance written alongside every result. The product contract lives in `docs/CAPABILITY_MATRIX.md`; a silently shrunk target pool aborts the run rather than biasing the FDR.

### Data access

**[MSMCP](https://github.com/janusson/MSMCP)** — mass spectrometry tools for AI clients over the Model Context Protocol ([msmcp.dev](https://msmcp.dev)). Spectra cross a tool boundary as server-side references, never as context-window payloads, and every derived result carries provenance. Search significance is deliberately uncalibrated, and the repository says so.

**[ChromaMCP](https://github.com/janusson/ChromaMCP)** — the chromatographic counterpart, scoped against USP `<621>`/`<1058>` and ICH Q2(R2)/Q14. Specification stage; no implementation yet.

### Computational chemistry

Collision cross-section determination for ion mobility–mass spectrometry, and substructure work. Private while unfinished.

## Elsewhere

- Writing and publications: [ericjanusson.ca](https://ericjanusson.ca)
- Email: [eric@ericjanusson.ca](mailto:eric@ericjanusson.ca)
