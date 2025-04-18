<img src="assets/2024_SEA_Logo2.png" width="40%" align="center">

# Improved Accessibility and Community Knowledge of Lidar and Radar Data Analysis

[![JupyterBook](https://github.com/UCAR-SEA/SEA-ISS-Template/actions/workflows/deploy.yml/badge.svg)](https://github.com/UCAR-SEA/SEA-ISS-Template/actions/workflows/deploy.yml)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-green?style=flat-square&logo=Jupyter&color=green)](https://jupyter.org/try)
![Static Badge](https://img.shields.io/badge/DOI-10.XXXXX%2Fnnnnn-blue)

**Authors**: Jennifer DeHart (1), Ana Victoria Espinoza (2), Brenda Javornik (3), Julien Chastang (2)

1) Department of Atmospheric Science
   Colorado State University
   Fort Collins, CO USA

2) NSF Unidata Program Center
   UCP, UCAR
   Boulder, CO USA

3) Earth Observing Laboratory
   NSF NCAR, UCAR
   Boulder, CO USA

**Abstract**:

To improve accessibility and community knowledge of applications in the Lidar Radar Open Software Environment (LROSE), a team from the National Science Foundation (NSF) National Center for Atmospheric Research, Colorado State University, and NSF Unidata has developed a lidar and radar meteorology science gateway deployed on the NSF Jetstream2 cloud. Utilizing the “Zero to JupyterHub with Kubernetes” workflow, the science gateway integrates LROSE with other lidar and radar meteorology software packages. This integration allows users to execute applications directly from the JupyterLab terminal, streamlining the creation of datasets for further analysis and visualization within Jupyter notebooks. By combining traditional command-line operations with modern Python-based tools for data analysis and visualization, this gateway provides a robust end-to-end solution that caters to both educational and research needs. The gateway has already facilitated LROSE instructional workshops and classroom exercises. Our work demonstrates the significant potential of merging established scientific computing techniques with advanced Python environments, opening new avenues for computational science education and research.

The LROSE team has acquired successive allocations on the NSF Jetstream2 cloud at Indiana University through ACCESS. To develop the LROSE Science Gateway, we employed the “Zero to JupyterHub with Kubernetes” workflow ported to the NSF Jetstream2 cloud, enabling rapid and scalable deployment to accommodate a variable number of users. Authentication is managed through either GitHub OAuth or temporary credentials, depending on the situation. Since LROSE is a collection of C/C++ applications, we configured Docker containers based on the Jupyter Docker Stack to integrate the LROSE software, available via the JupyterLab terminal. These containers also include Conda package manager environments equipped with Python packages like Py-ART, CSU RadarTools, and Metpy for further data analysis. A shared drive accessible to all participants contains instructional datasets for lidar and radar data analysis.

Tutorials take the form of Jupyter notebooks for use by individuals, in classroom exercises, or at instructional workshops. Some tutorials are complete with pre-loaded examples to quickly visualize workflows and results. Other tutorials guide students how to run the applications independently. All tutorials are hosted on the LROSE Science Gateway GitHub repository, which is open to contributions from colleagues and community members.

Future plans include an "intermediate" level workshop on SAMURAI, one of the multi-Doppler wind applications of the LROSE suite. Additionally, work is currently underway to run GUI applications in the same browser-based JupyterLab environment. GUI applications for radar and lidar data visualization utilize the QT framework and present unique technical challenges. The techniques to accomplish GUI access have immediate applications for other GUI programs, such as NFS Unidata's IDV and their version of the AWIPS CAVE data visualization tools. Lastly, as demand for the resources found on the gateway increases, it becomes increasingly important to efficiently manage the Jetstream2 resources allocated by the ACCESS program. LROSE, NSF Unidata, San Diego Supercomputing Center (SDSC), and Indiana University staff are working together to deploy and evaluate Kubernetes cluster auto-scaling. With autoscaling, resources will no longer sit idle while awaiting new logins and will instead be provisioned on-demand. 

**Keywords:** open source, radar, lidar, science gateway, LROSE

**Acknowledgements**: [List any Acknowledgements]
