# scitt-scrapi-dependencytrack

This repo will host end-to-end docs for SCITT and SCRAPI, covering a
reference Transparency Service flow plus Dependency-Track SBOM receipt
verification and refresh demos.

Planned scope:

- `go-scitt-scrapi` reference implementation [1] notes: a Go SCITT Transparency
  Service implementing the SCRAPI REST API (implementing [2] [3]), plus a CLI
  to issue signed statements and verify receipts.
- Dependency-Track integration walkthroughs, including receipt verification
  and SCRAPI refresh flows [4] [5].

References:

- [1] https://github.com/mhlotto/go-scitt-scrapi
- [2] https://www.ietf.org/archive/id/draft-ietf-scitt-architecture-22.txt
- [3] https://www.ietf.org/archive/id/draft-ietf-scitt-scrapi-05.txt
- [4] https://github.com/DependencyTrack/dependency-track
- [5] https://github.com/mhlotto/dependency-track
