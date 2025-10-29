# UNSW-NB15 Dataset

The **UNSW-NB15** source files (**pcap files**, **BRO files**, **Argus files**, **CSV files**, and **reports**) can be downloaded from **[HERE](https://research.unsw.edu.au/projects/unsw-nb15-dataset)**.  
You can also use our new datasets created in the **TON_IoT** project.

---

## Dataset Description

The raw network packets of the **UNSW-NB15 dataset** were created by the **IXIA PerfectStorm** tool in the **Cyber Range Lab** of **UNSW Canberra**.  
This setup generated a hybrid of real modern normal activities and synthetic contemporary attack behaviours.  
The `tcpdump` tool was used to capture **100 GB** of raw traffic (i.e., Pcap files).

This dataset includes **nine types of attacks**:

- Fuzzers  
- Analysis  
- Backdoors  
- DoS  
- Exploits  
- Generic  
- Reconnaissance  
- Shellcode  
- Worms  

The **Argus** and **Bro-IDS** tools were used, and **twelve algorithms** were developed to generate **49 features** (plus the class label).  
These features are described in the `UNSW-NB15_features.csv` file.

---

## Dataset Files

- Total records: **2,540,044**
- Stored in four CSV files:
  - `UNSW-NB15_1.csv`
  - `UNSW-NB15_2.csv`
  - `UNSW-NB15_3.csv`
  - `UNSW-NB15_4.csv`
- Ground truth table: `UNSW-NB15_GT.csv`
- Event list file: `UNSW-NB15_LIST_EVENTS.csv`

A partition of this dataset is configured as:

- **Training set:** `UNSW_NB15_training-set.csv` (175,341 records)
- **Testing set:** `UNSW_NB15_testing-set.csv` (82,332 records)

Both contain records from different attack and normal categories.

---

## Publications and Citations

The details of the UNSW-NB15 dataset were published in the following papers.  
For **academic or public use**, you **must cite** the following works:

1. Moustafa, Nour, and Jill Slay.  
   *"UNSW-NB15: A comprehensive data set for network intrusion detection systems (UNSW-NB15 network data set)."*  
   *Military Communications and Information Systems Conference (MilCIS), IEEE, 2015.*

2. Moustafa, Nour, and Jill Slay.  
   *"The evaluation of Network Anomaly Detection Systems: Statistical analysis of the UNSW-NB15 dataset and the comparison with the KDD99 dataset."*  
   *Information Security Journal: A Global Perspective (2016): 1–14.*

3. Moustafa, Nour, et al.  
   *"Novel geometric area analysis technique for anomaly detection using trapezoidal area estimation on large-scale networks."*  
   *IEEE Transactions on Big Data (2017).*

4. Moustafa, Nour, et al.  
   *"Big data analytics for intrusion detection system: statistical decision-making using finite Dirichlet mixture models."*  
   *Data Analytics and Decision Support for Cybersecurity. Springer, Cham, 2017. pp. 127–156.*

5. Sarhan, Mohanad, Siamak Layeghy, Nour Moustafa, and Marius Portmann.  
   *"NetFlow Datasets for Machine Learning-Based Network Intrusion Detection Systems."*  
   *In Big Data Technologies and Applications, Springer, 2020.*

---

## Related Research and Recommended Citations

The authors have also published papers on **Intrusion Detection**, **Network Forensics**, **Privacy-Preserving**, and **Threat Intelligence** approaches in different systems such as **IoT**, **SCADA**, **Industrial IoT**, and **Industry 4.0**.  
You are encouraged to cite the following works when comparing with your studies:

- Moustafa, Nour, et al. *"An Ensemble Intrusion Detection Technique based on proposed Statistical Flow Features for Protecting Network Traffic of Internet of Things."* IEEE Internet of Things Journal (2018).  
- Koroniotis, Nickolaos, Moustafa, Nour, et al. *"Towards Developing Network Forensic Mechanism for Botnet Activities in the IoT Based on Machine Learning Techniques."* International Conference on Mobile Networks and Management. Springer, Cham, 2017.  
- Moustafa, Nour, et al. *"Generalized Outlier Gaussian Mixture technique based on Automated Association Features for Simulating and Detecting Web Application Attacks."* IEEE Transactions on Sustainable Computing (2018).  
- Keshk, Marwa, Moustafa, Nour, et al. *"Privacy preservation intrusion detection technique for SCADA systems."* Military Communications and Information Systems Conference (MilCIS), 2017. IEEE, 2017.  
- Moustafa, Nour, et al. *"A New Threat Intelligence Scheme for Safeguarding Industry 4.0 Systems."* IEEE Access (2018).  
- Moustafa, Nour, et al. *"Anomaly Detection System Using Beta Mixture Models and Outlier Detection."* Progress in Computing, Analytics and Networking. Springer, 2018.  
- Moustafa, Nour, et al. *"Flow Aggregator Module for Analysing Network Traffic."* Progress in Computing, Analytics and Networking. Springer, 2018.  
- Moustafa, Nour, et al. *"A Network Forensic Scheme Using Correntropy-Variation for Attack Detection."* IFIP International Conference on Digital Forensics. Springer, Cham, 2018.

---

## Thesis Reference

For detailed algorithmic descriptions of the features used in the UNSW-NB15 dataset, please cite:

> **Moustafa, Nour.**  
> *Designing an online and reliable statistical anomaly detection framework for dealing with large high-speed network traffic.*  
> PhD Dissertation, University of New South Wales, Canberra, Australia, 2017.

---

## License and Usage

Free use of the **UNSW-NB15 dataset** for **academic research purposes** is granted in perpetuity.  
Use for **commercial purposes** requires agreement from the authors.

**Copyright Notice:**  
Nour Moustafa and Jill Slay have asserted their rights under copyright law.  
Anyone intending to use the UNSW-NB15 dataset **must cite the above five papers**.

---

## Contact

For more information about the datasets, please contact:

**Dr. Nour Moustafa**  
📧 Email: [nour.moustafa@unsw.edu.au](mailto:nour.moustafa@unsw.edu.au) | [nour.moustafa@ieee.org](mailto:nour.moustafa@ieee.org)

More information about Dr. Nour Moustafa:
- [UNSW Profile](https://www.unsw.adfa.edu.au/our-people/dr-nour-moustafa)
- [Research Profile](https://research.unsw.edu.au/people/dr-nour-moustafa-abdelhameed-moustafa)
- [LinkedIn](https://www.linkedin.com/in/nour-moustafa-0a7a7859/)

---

**Dataset Source:**  
[https://research.unsw.edu.au/projects/unsw-nb15-dataset](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
