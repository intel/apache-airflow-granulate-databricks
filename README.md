# Granulate Airflow-Databricks Integration Packages

This repository contains two packages designed to enhance Apache Airflow's integration with Databricks, using Granulate's performance monitoring technology. These packages allow easy and efficient integration of Granulate's optimization capabilities into your Airflow-Databricks workflows.

## Packages Overview

### 1. apache-airflow-granulate-databricks

The `apache-airflow-granulate-databricks` package is an open-source plugin for Apache Airflow. It facilitates the integration of Granulate's performance monitoring agent with Databricks jobs orchestrated by Airflow. This package offers several modes of operation, including passive mode, auto-patch for specific DAGs, and auto-patch for all DAGs.

**Key Features:**
- Manual and automatic patching of Databricks operators.
- Compatibility with Databricks Airflow Provider versions 4.2.0 to 6.5.0.
- Supports Python version 3.8 or higher.

For detailed information, installation instructions, and usage guidelines, see the [README](./apache-airflow-granulate-databricks/README.md) in its directory.

### 2. apache-airflow-granulate-databricks-auto-patch

The `apache-airflow-granulate-databricks-auto-patch` package acts as a flag for enabling the 'auto-patch' feature in the `apache-airflow-granulate-databricks` package. It simplifies the process of automatically applying Granulate's enhancements to all DAGs in your Airflow environment.

**Purpose:**
- Used in conjunction with the main plugin to enable global auto-patching.
- Automates the inclusion of `GRANULATE_JOB_NAME` in Databricks jobs across all DAGs.

For more information on this package, refer to its [README](./apache-airflow-granulate-databricks-auto-patch/README.md).

## Installation

To use these packages, you can install them via pip, as detailed in the individual READMEs. Ensure you choose the correct installation method based on your desired mode of operation.

## Support

For support, questions, or issues related to either of these packages, please open an issue in this GitHub repository. We aim to provide timely and helpful responses to all inquiries.

## License

Both packages are licensed under the Apache License 2.0. For more details, see the [LICENSE](LICENSE) file.
