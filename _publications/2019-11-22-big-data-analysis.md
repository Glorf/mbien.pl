---
title: "Paper Title Number 1"
collection: publications
permalink: /publication/2019-11-22-big-data-analysis
excerpt: 'This work has successfully deployed two different use cases of interest for High Energy Physics 
using cloud resources.'
date: 2019-11-22
venue: 'CERN Openlab Zenodo'
paperurl: 'https://zenodo.org/record/3550777'
citation: '@misc{michal_bien_2019_3550777,
  author       = {Michał Bień},
  title        = {{Big Data Analysis and Machine Learning  at Scale 
                   with Oracle Cloud Infrastructure}},
  month        = nov,
  year         = 2019,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.3550777},
  url          = {https://doi.org/10.5281/zenodo.3550777}
}'
---
This work has successfully deployed two different use cases of interest for High Energy Physics using cloud resources:

* CMS Big data reduction: This use case consists in running a data reduction workloads for physics data. The code and implementation has originally been developed by CERN openlab in collaboration with CMS and Intel in 2017-2018. It aims at demonstrating the scalability of a data reduction workflow, by processing ROOT files using Apache Spark
* Spark DL Trigger: This use case consists in the deployment of a full data preparation and machine learning pipeline, starting from data ingestion (4.5 TB of ROOT data), to the training of classifier using neural networks. This use case is implemented using Apache Spark and the Keras API, following previous work in collaboration with CERN openlab.

Notable results of this project:

* Produced several key improvements to the oci-hdfs-connector. The improvements are necessary to run the latest Spark version (Spark 2.4.x) on Oracle Cloud. The connector is distributed by Oracle with open source licensing, and the improvements will be fed back to Oracle.
* Improved instrumentation infrastructure for measuring Spark workloads on cloud resources, by streamlining the deployment of Spark performance dashboard on Kubernetes and developing a Helm chart
* Produced a solution for direct measurement of I/O latency for Spark workloads reading from OCI or S3 storage. The results are of general interest for Spark users, notably including the Spark service at CERN
* Developed methods to parallelize TensorFlow/Keras on Kubernetes using TensorFlow 2.0 new tf.distribute features. These are of general interest for ML practitioners, notably including the users of CERN cloud services.

[Download paper here](https://zenodo.org/record/3550777/files/Report_Michal_Bien.pdf?download=1)

Recommended citation:

```bibtex
@misc{michal_bien_2019_3550777,
  author       = {Michał Bień},
  title        = {{Big Data Analysis and Machine Learning  at Scale 
                   with Oracle Cloud Infrastructure}},
  month        = nov,
  year         = 2019,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.3550777},
  url          = {https://doi.org/10.5281/zenodo.3550777}
}
```
