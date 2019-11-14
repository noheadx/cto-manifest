# cto-manifest
## TOC
1. Motivation
_guidelines to enable the team working; We strive to deliver a fast, scalable and resilient platform that provides easy and verifiable access to clinical trial data for patients, sites and sponsors._
2. Agile Manifesto
_Small, vertical stories; no separation backend/frontend; constant communication between internally and with stakeholders; constant improvement on way of working_
3. Release
_no personal dependencies on release; release automation(CI); trust in releases (good night's sleep); feedback on success/failure_
4. Container
_built once - runs anywhere; releases are deployed as containers in any environment; we don't rely on pre-build images for security reasons but rather build them ourselves_
5. Quality
_we care for each story that we deliver from end to end; we pair for coding; every story is shipped with tests (TDD); we do code reviews; no release goes out untested; regular smoke tests on production_
6. Infrastructure
_we don't own/maintain hardware ourselves; we rely on the expertise of IaaS providers to provide infrstructure services world-wide; if a service is not provided, we will build it; we are aware of the performance of our platform on the technical and business side_
7. Architecture
_we enforce a loose-coupled architecture by deploying functionalities in smaller services; we keep the business logic where it belong; our services work with a communication pattern that allows to be easily extended to with additional services_
8. Security
_we encrypt data at rest and transmission; we don't store passwords in clear text; we reduce external access to our platform; we seggregate all environments; we work with anonymized data only;_


## Remarks
ad 4.), 6.), 7.) I think we need additional documents for these points, describing in deeper technical detail the Dos and Don'ts for each section, like API/Docker style guides, managing cloud infrastructures, etc.
