<p align="center">
  <h1 align="center">DeltaLake Lakehouse</h1>
  <p align="center">
    <a href="README_ZH.md"><strong>简体中文</strong></a> | <strong>English</strong>
  </p>

## Table of Contents

- [Repository Introduction](#repository-introduction)  
- [Prerequisites](#prerequisites)  
- [Image Specifications](#image-specifications)
- [Getting Help](#getting-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction  
[DeltaLake](https://github.com/delta-io/delta)  is an open-source storage layer built on top of existing data lakes (such as Hadoop Distributed File System (HDFS), Amazon S3, Azure Data Lake Storage, etc.), bringing reliability, transactional, and ACID (atomicity, consistency, isolation, persistence) features to the data lake.

**Core Features:**
1. ACID transaction guarantee: Delta Lake implements complete ACID transactions through Multi Version Concurrent Control (MVCC) mechanism.
2. Scalable metadata management: Delta Lake utilizes Spark's distributed processing capabilities to handle PB level table metadata, supporting metadata management for billions of files.
3. Unified stream batch processing: The Delta table serves as both a batch processing table and a stream source and receiver, achieving true stream batch integration.
4. Time Travel: Delta Lake supports data version control and allows querying historical data snapshots.
5. A vibrant connector ecosystem: Delta Lake has connectors for reading and writing Delta tables from various data processing engines, such as Apache Spark, Apache Flink, Apache Hive, and Apache Trino.

**Architecture Design:**

![](./images/img001.png)

This project offers pre-configured [**DeltaLake Lakehouse**](https://marketplace.huaweicloud.com) images with DeltaLake and its runtime environment pre-installed, along with deployment templates. Follow the guide to enjoy an "out-of-the-box" experience.

> **System Requirements:**
> - CPU: 4GHz or higher  
> - RAM: 8GB or more  
> - Disk: At least 60GB  

## Prerequisites  
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Specifications  

| Image Version                                                  | Description                                             | Notes |  
|----------------------------------------------------------------|---------------------------------------------------------|-------|  
|  [deltaLake4.0.0-kunpeng-v1.0](https://github.com/HuaweiCloudDeveloper/DeltaLake-image/tree/deltaLake4.0.0-kunpeng-v1.0) | Deployed on Kunpeng servers with Huawei Cloud EulerOS 2.0 64bit |  | 

## Getting Help
- Submit an [issue](https://github.com/HuaweiCloudDeveloper/DeltaLake-image/issues)
- Contact Huawei Cloud Marketplace product support

## How to Contribute
- Fork this repository and submit a merge request.
- Update README.md synchronously based on your open-source mirror information.
