# ComPat Software

ComPat is a science driven project on Computing Patterns for High Performance Multiscale Computing. 
This page is a hub repository linking to the the software output of the ComPat project.
You can find more information about ComPat at http://www.compat-project.eu.

## FabSim
FabSim is a Python-based automation toolkit for scientific simulation and data processing workflows, licensed under the BSD 3-clause license. It aims to enable users to perform remote tasks from a local command-line, and to run applications while curating the environment variables and the input and output data in a systematic manner. To provide that curation, FabSim uses a basic data transfer functionalities such as rsync and ssh.

| Component        | Description                | Webpage                                         | Repository  |
| ---------------- | -------------------------- | ----------------------------------------------- | ----------- |
| FabSim           | The automation toolkit     | https://github.com/UCL-CCS/FabSim | https://github.com/UCL-CCS/FabSim |

## QCG – Quality in Cloud and Grid 
The QCG middleware (previously known as QosCosGrid) is an integrated system offering advanced job and resource management capabilities to deliver to end-users supercomputer-like performance and structure. By connecting many distributed computing resources together, QCG offers highly efficient mapping, execution and monitoring capabilities for variety of applications, such as parameter sweep, workflows, MPI or hybrid MPI-OpenMP. Thanks to QCG, large-scale applications, multi-scale or complex computing models written in Fortran, C, C++ or Java can be automatically distributed over a network of computing resources with guaranteed QoS. The middleware provides also a set of unique features, such as advance reservation and co-allocation of distributed computing resources.

<img src="/resources/qcg-wb.png?raw=true" width="200">

| Component        | Description                | Webpage                                         | Repository  |
| ---------------- | -------------------------- | ----------------------------------------------- | ----------- |
| QCG-Broker       | The brokering service      | http://www.qoscosgrid.org/trac/qcg-broker       | http://repository.qcg.psnc.pl/compat/ |
| QCG-Computing    | The computing service      | http://www.qoscosgrid.org/trac/qcg-computing    | http://repository.qcg.psnc.pl/compat/ |
| QCG-Notification | The notification subsystem | http://www.qoscosgrid.org/trac/qcg-notification | http://repository.qcg.psnc.pl/compat/ |
| QCG-PilotJob     | Pilot Job service          | https://github.com/compat-project/QCG-PilotJob  | https://github.com/compat-project/QCG-PilotJob |
| QCG-Client       | Client tool for QCG-Broker | http://www.qoscosgrid.org/trac/qcg-broker/wiki/client_user_guide | http://repository.qcg.psnc.pl/compat/ |

## MUSCLE 2
MUSCLE 2 – The Multiscale Coupling Library and Environment – is a portable framework to do multiscale modeling and simulation on distributed computing resources. The generic coupling mechanism of MUSCLE is suitable for many types of multiscale applications, notably for multiscale models as defined by the MAPPER project. Submodels can be implemented from scratch, but legacy code can also be used with only minor adjustments. The runtime environment solves common problems in distributed computing and couples submodels of a multiscale model, whether they are built for high-performance supercomputers or for local execution. MUSCLE supports Java, C, C++, Fortran, Python, MATLAB and Scala code, using MPI, OpenMP, or threads.

| Component        | Description                | Webpage                                         | Repository  |
| ---------------- | -------------------------- | ----------------------------------------------- | ----------- |
| MUSCLE2          | The coupling toolkit       | https://github.com/psnc-apps/muscle2/tree/compat | https://github.com/psnc-apps/muscle2/tree/compat |

## Patterns software
The Patterns software maps submodels to the required architecture to abstract this complexity from user. It generates/submit middleware files required.

| Component        | Description                | Webpage                                         | Repository  |
| ---------------- | -------------------------- | ----------------------------------------------- | ----------- |
| PatternDrivenPlans | Maps submodels to architecture | https://github.com/compat-project/PatternDrivenPlans | https://github.com/compat-project/PatternDrivenPlans |

## Custom metric plugins

Provides custom metric plugins for Arm Forge Professional, Arm Performance Reports and other compatible software.

| Component        | Description                | Webpage                                         | Repository  |
| ---------------- | -------------------------- | ----------------------------------------------- | ----------- |
| Custom metric plugins | Custom metric plugins | https://github.com/compat-project/custom-metrics | https://github.com/compat-project/custom-metrics |

## AMUSE
AMUSE – The Astrophysical MUltipurpose Software Environment – a software framework that provides a homogeneous interface to a wide variety of packages, which enables the research of astrophysical phenomena where complex interactions occur between different physical domains. The framework can be used for astrophysical simulations, in which existing codes from different domains, such as stellar dynamics, stellar evolution, hydrodynamics and radiative transfer can be easily coupled

<img src="/resources/AmuseLogo.png?raw=true" width="100">

| Component        | Description                | Webpage                                         | Repository  |
| ---------------- | -------------------------- | ----------------------------------------------- | ----------- |
| AMUSE            | Astrophysical Multipurpose Software Environment | http://amusecode.org/ | https://github.com/amusecode |

## ECOS - Energy Consumption Optimization Service

The ECOS program reads values from performance counters every fixed period of time. Based on these values it decides whether to increase or decrease the frequency of the processor. The program controls independently the frequencies for each hardware thread in the system (according to the division nomenclature: processor -> core -> hardware thread). In the case of a decision to change the frequency, it is changed by 100MHz, so the change between the maximum and minimum frequency of the processor usually takes several program cycles (one cycle is understood as the operation of reading meters for each thread, the decision to change the frequency and its potential execution). Frequency change is forced by writing the new maximum frequency for the hardware thread and it is specified in the file /sys/devices/system/cpu/cpu/cpu/cpufreq/scaling_max_freq, this method is compatible with cpufreq and intel-pstate.

| Component        | Description                | Webpage                                         | Repository  |
| ---------------- | -------------------------- | ----------------------------------------------- | ----------- |
| ECOS             | Energy Consumption Optimization Service | https://github.com/compat-project/ECOS | https://github.com/compat-project/ECOS |
