# Nordic32 test system (old version)

**File** : *Long term dynamics. Phase II. Final Report.pdf*  
**Note**: Original version.

---

# Nordic Test System (variant of Nordic32)

**File**: *Test systems for voltage stability studies.pdf*  
**Note**: The link for downloading the Technical Report (PES-TR19 Test Systems for Voltage Stability Analysis and Security Assessment) cannot be accessed anymore (the provided link leads to a "Not found" page) but this file describes the test system set up in that Technical Report.  
**Source**: [https://orbi.uliege.be/bitstream/2268/245565/1/Paper_R2.pdf](https://orbi.uliege.be/bitstream/2268/245565/1/Paper_R2.pdf)

**File**: *Nordic_test_system_V6.pdf*  
**Note**: Older than *Test systems for voltage stability studies.pdf* (November 2013) – Potentially a bit different.  
**Source**: [https://orbi.uliege.be/bitstream/2268/141234/1/Nordic_test_system_V6.pdf](https://orbi.uliege.be/bitstream/2268/141234/1/Nordic_test_system_V6.pdf)


**Source of the following files:** [https://cmte.ieee.org/pes-psdp/489-2/](https://cmte.ieee.org/pes-psdp/489-2/)

*NB*: “This web page contains information about the work of the IEEE PES Task Force on Test Systems for Voltage Stability Analysis and Security Assessment. Full data and samples of representative outputs (…) can be found in this page. The sampled outputs refer to long-term dynamic simulations of their responses to large disturbances.“

**Folder**: Nordic_resultsaA  
**Note**: Sample output results in ASCII format

**Folder**: Nordic_ramses_dat  
**Note**: Input data for RAMSES.

**Folder**: PSSE_files_A  
**Note**: Input data for PSS/E.

**Folder**: Nordic_anatem_dat  
**Note**: Input data for ANATEM.

**File**: Nordic_Test_System.pfd  
**Note**: Input data for DigSilent Power Factory.

---

# Nordic32 extended for cyber-physical study

**Note**: In *Quantitative Evaluation of the Efficacy of Defence-in-Depth in Critical Infrastructures*, the authors study a model-based approach to assessing the cyber-risks in a cyber-physical system. They provide some results concerning a quantitative assessment of cyber-risks in such systems and in order to do that they use the Nordic32 extended with measurement, protection and control, all in compliance with the standard IEC 61850 for interoperable substations.

The following **folder** contains:

- a high-performance agent-based simulation engine used for stochastic simulation of complex cyber-physical systems

- **the set of models (json files) related to the Nordic32** extended with a models of SCADA and substations instrumentation/measurement, compliant with IEC 61850.

**Folder**: nordic32-extended  
*NB: Data can be found in* models.  
**Source**: [https://openaccess.city.ac.uk/id/eprint/19330/](https://openaccess.city.ac.uk/id/eprint/19330/)

---

# TDNetGen

Open-source MATLAB toolbox able to generate synthetic, large-scale, combined transmission and distribution network models. **TDNetGen** generates a combined T&D test system using the **Nordic Test System** model and replacing the aggregated transmission grid loads with a detailed distribution grid model.  
**Source**: [TDNetGen repository](https://github.com/apetros/TDNetGen)