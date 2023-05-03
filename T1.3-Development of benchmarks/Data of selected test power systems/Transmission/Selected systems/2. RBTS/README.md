# Roy Billinton Test System
The following documents contain descriptions, one-line diagrams and data tables of the RBTS.

**File**: *A reliability test system for educational purposes-basic data.pdf*  
**Note**: First version – No distribution

**File** : *A reliability test system for educational purposes-basic distribution system data and results.pdf*  
**Note**: First extension of the RBTS with buses 2 and 4 extended into distribution systems.

**File** : *A test system for teaching overall power system reliability assessment.pdf*  
**Note**: Second extension of the RBTS with buses 3, 5 and 6 extended into distribution systems

**File** : Appendix A of *Reliability Assessment of Electric Power Systems Using Monte Carlo Methods.pdf*  
**Note**: Description and data of the RBTS and its extended version.


The only data found is a m-file containing an improvement of the distribution system extension of bus 2 originally found in *A reliability test system for educational purposes-basic distribution system data and results*:

**Files**: ImpRBTSbus2.m & RBTS_Bus_2.pdf  
**Note**: Matpower code & Topology of the distribution system extension of bus 2.  
**Source**: [Improved RBTS Bus 2 test system data for power system reliability assessment and risk management studies](https://data.mendeley.com/datasets/v4sdczmg38/1)

## New files

**Folder:** OPF data

- RBTS.py: OPF data in pandapower format
- RBTS_ACOPF_peak.iidm: load flow resulting from an ACOPF (no security constraints) on the above data at peak load exported to Dynawo/PowSyBl format

Dynamic data and models on [https://github.com/FredericSabot/dynawo/tree/9_Cosim/examples/DynaSwing/RBTS](https://github.com/FredericSabot/dynawo/tree/9_Cosim/examples/DynaSwing/RBTS) (to be refined)
