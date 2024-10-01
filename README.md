# DBT Concepts Overview

This document provides a brief explanation of the major concepts in DBT.

- **Models** 📊: SQL files that transform raw data into analysis-ready datasets. They are built using `SELECT` statements and are the core building blocks of DBT.
  
- **Sources** 🏭: Represent raw data from external systems, allowing you to reference and document the data sources used by DBT models.

- **Seeds** 🌱: CSV files stored in your DBT project and loaded into the data warehouse as tables for use in transformations.

- **Snapshots** 📸: Capture the historical state of a table at regular intervals, enabling you to track changes over time for slowly changing dimensions (SCDs).

- **Tests** ✅: Assertions about your data’s integrity and quality, such as ensuring non-null, uniqueness, or referential integrity in models and sources.

- **Documentation** 📚: Allows you to write descriptions for models, columns, and tests to create a detailed data dictionary or project documentation.

- **Macros** 🔄: Reusable SQL snippets or logic, written in Jinja, that allow you to create more dynamic and flexible models or tests.

- **Configs** ⚙️: Settings that control model behavior (like materialization strategies) and other operational aspects, applied at the project or model level.
