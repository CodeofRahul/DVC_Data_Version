# DVC_Data_Version
This repo implements the idea of data versioning using DVC tool

**In MLOPS (Machine Learning Operations), data versioning plays a vital role in ensuring the reproducibility, reliability, and scalability of machine learning models.**

## Data Version Control (DVC)

**1. Data Set Versioning:** DVC enables versioning of large datasets, allowing you to track changes and reproduce experiments. This is particularly important in machine learning projects where data quality and consistency are critical.

**2. Data Reproducibility:** By versioning data, DVC ensures that the same data is used for training and testing models, ensuring reproducibility and reducing the risk of errors or inconsistencies.

**3. Experiment Tracking:** DVC integrates with Git, allowing you to track experiments and model versions alongside code changes. This provides a complete history of model development and enables easy comparison of different experiments.

**4. Cache Management:** DVC caches data and model outputs, reducing the need to re-compute or re-download large datasets. This accelerates experimentation and improves collaboration.



## Data versioning

**1. Reproducibility:** Data versioning enables you to track changes to datasets, models, and code, ensuring that you can reproduce previous results and experiments. This is particularly important in machine learning, where small changes can have significant impacts on model performance.

**2. Collaboration:** Data versioning facilitates collaboration among team members by providing a single source of truth for data changes, model updates, and code modifications. This ensures that everyone is working with the same version of the data and models.

**3. Rollback and Recovery:** In case of errors or model degradation, data versioning enables you to quickly revert to a previous version of the data, model, or code, minimizing downtime and ensuring business continuity.





## Git commands 

- To add all file = `git add .`
- To add any particular file = `git add <file_name>`
- To commit = `git commit -m "commit message"`
- To push the code = `git push origin main`

## DVC commands

- To install dvc = `pip install dvc`
- To initializ dvc = `dvc init`
- To add dvc remote = `dvc remote add -d <remote url>`
- To commit = `dvc commit`
- To push = `dvc push`
- Start tracking file = `dvc add <file>`
