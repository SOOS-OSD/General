# Southern Ocean Observing System

## Observing System Design (OSD) Capability Working Group

The [Observing System Design (OSD) Capability Working Group](https://www.soos.aq/activities/cwg/osd) developed from the need to quantify the minimal amount of data required to address specific quantities or variables of interest. This work supports efforts to gain greatest scientific benefit from limited resources. The working group  aims to facilitate the design of a comprehensive and multi-disciplinary observing system for the Southern Ocean by analyzing methods, providing guidance for optimizing observational strategies and seeking to enhance collaboration and instigate discussions on this important topic. 


#### Goals

######Provide the following deliverables: 

1. Build a network of interested members and stakeholders, including a committed  leadership team.

2. Identify Observing System Design projects (e.g. for graduate students or more  advanced researcher) for specific stakeholders and/or working groups (e.g. Ross Sea MPA)

3. Contribute to workshops (e.g. a planned SORP/OSD/SOFLUX workshop)

4. Contributions to the BAMS State of the Climate report


#### Terms of reference and general goals

1. Compile a list of tools used across disciplines for observing system design and evaluation: statistical methods exist in other disciplines (e.g terrestrial ecology and hydrography).

2. Compile a list of quantities of interest (QoIs) or classes of QoIs that methods of observing system evaluation must be able to handle. The observing system design depends on the QoI. The QoI could be an essential ocean variable (EOV; e.g. T, S, Fe, O2, pH….), or it could be driven by a scientific question (e.g. upper ocean property content, water mass formation rate, upwelling rate, downwelling rate, mixed layer depth, mixing layer depth, thermocline depth, ice export, NCP, NPP, O2 sat, aragonite saturation). We may want to declare all EOVs QoIs, and then ask other panels (e.g. SORP) for a list of other science-based QoIs. This deliverable may also be considered a task of SOOS objective 1 in the SOOS implementation plan.

3. Establish a method to determine spatial and temporal correlation scales for classes of QoIs listed in deliverable 2. A method for estimating the correlation scales in time and space of all QoIs should be presented and assessed. This gives a first guess at observational density requirements. When feasible scales should be calculated and published.

4. Establish a method to determine cross-correlation scales for classes of QoIs listed in deliverable 2. True system design needs to account for cross-correlation between the QoI and all observables. This is a more complex problem of greater dimension. We can break this into two steps:

a) Determine methodology to estimate cross-covariance magnitude between a QoI and an observable. Observables that strongly covary with classes of QoIs should be noted.

b) Determine the cross-correlation scales for variables that strongly covary. This follows on 3 and 4A, in that it informs how to constrain a QoI. However, we may want to publish a statement on how the current observing system (Argo, SST, SSH, sea ice area) informs other quantities of interest (e.g. pH). We may also want to recommend enhancements to the current observing system for observables that strongly covary with QoIs, but are currently poorly constrained.

5. Provide methods for investigators (e.g. regional working groups) to design an observing system to constrain their chosen QoIs. This uses information from 3 and 4 to inform constraining QoIs. It must account for correlation vs covariance in terms of the chosen QoI by addressing the question: if a location is weakly varying is it as important to constrain as a region that is strongly varying? The primary tool to be employed here is some form of a mapping algorithm in which reconstruction errors can be quantified for an ensemble of observing system design experiments (OSSEs).

6. Development of a user-friendly open-source OSSE tool. Enable straightforward OSSE investigations by developing tools that can be configured at runtime allowing non-experts to readily explore the methods, and removing the burden to write, configure, and compile code. Provide either a downloadable executable or a web interface where a user provides a netcdf vector of observations of any component of the system and is returned informational maps and statistics estimating how well that observational vector constrains their QoI. This must account for cross-correlation. Providing an ensemble of observational vectors quantifies the “goodness” of their observational strategy.