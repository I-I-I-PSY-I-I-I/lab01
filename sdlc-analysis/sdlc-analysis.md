# SDLC Origin-Detection Analysis: Healthcare.gov Launch

## Failure Mapping Matrix

| Engineering Defect / Problem | Origin Phase | Detection Phase | Analysis & Impact |
| :--- | :--- | :--- | :--- |
| **Changing Requirements (C1)** | Requirements | Requirements Review / Testing | System requirements continuously evolved while active development was already underway, forcing constant rework. These shifts should have been managed through strict change control and caught during testing. |
| **System Integration Issues (C3/C9)** | Design | Integration Testing | The platform relied on dozens of separate systems and contractors that ultimately failed to work together. Comprehensive end-to-end integration testing before launch should have identified these broken connections. |
| **Late Development & Rework (C9)** | Implementation | Testing / Release Review | Coding and system changes continued right up to the launch date, which severely cut into the time needed to test and fix bugs. Routine project reviews should have flagged that the software was too immature for public release. |
| **Insufficient Testing (C5)** | Testing | Operation | The team lacked the time required to test the complete system under realistic, real-world scenarios. Because of this, major functional problems were only discovered after live users began accessing the site. |
| **Performance & Capacity Limitations (C3/C5)** | Design | Performance Testing / Operation | The system was fundamentally unable to handle the massive volume of concurrent users. Capacity should have been planned during the design phase and validated with heavy stress testing, but instead, the system simply crashed during live operation. |
| **Schedule Pressure (C9)** | Project Management | Release Review | An unmovable launch deadline forced the team to push forward despite glaring, unresolved technical problems. A rigorous release-readiness review should have halted the launch until the system was stable. |
| **Launch Problems (C7)** | Release | Operation | The portal was deployed to the public while still carrying significant, known defects. Once it went live, users were immediately hit with timeouts, incredibly slow load speeds, and widespread errors preventing application completion. |
