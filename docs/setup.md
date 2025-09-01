# Project Setup Guide

This guide explains how to setup the Azure Data Warehouse Pipeline for this project.

---

## 1️⃣ Prerequisites

- Microsoft Azure subscription with:
    - Azure Date Lake Gen2
    - Azure Data Factory
    - Azure Synapse Analytics
- Power BI Desktop.
- Git (To clone this project).

---

## 2️⃣ Clone the Repository

```sh
git clone https://github.com/mohammedOwaiskh/retail-data-warehouse.git 
cd retail-data-warehouse
```
---
## 3️⃣Configure Azure Resources

1. Data Lake
    - Create a storage account with LRS Replication and Hierarchical namespace enabled.
    - Add 3 containers for the medallion layers:
        - <code>/bronze</code>
        - <code>/silver</code>
        - <code>/gold</code>