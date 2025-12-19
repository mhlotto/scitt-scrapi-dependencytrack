# scitt-scrapi-dependencytrack

This repo will contain end-to-end docs for SCITT and SCRAPI, including a
reference Transparency Service flow and Dependency-Track verification and
refresh demos [1].

Planned scope:

- `go-scitt-scrapi` reference implementation notes: a Go SCITT Transparency
  Service implementing the SCRAPI REST API (implementing [2] [3]), plus a CLI
  to issue signed statements and verify receipts.
- Dependency-Track integration walkthroughs, including receipt verification
  and SCRAPI refresh flows [1].

References:

- [1] https://github.com/DependencyTrack/dependency-track
- [2] https://www.ietf.org/archive/id/draft-ietf-scitt-architecture-22.txt
- [3] https://www.ietf.org/archive/id/draft-ietf-scitt-scrapi-05.txt
