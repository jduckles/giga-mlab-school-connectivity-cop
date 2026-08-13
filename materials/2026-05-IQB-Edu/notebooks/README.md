# IQB-Edu: the Moldova use case

([back to IQB-Edu materials](../README.md))

- [IQB-Edu_Moldova_schools.ipynb](./IQB-Edu_Moldova_schools.ipynb): Notebook that loads M-Lab / Giga Meter measurements for schools in Moldova, calculates IQB scores, and presents main findings - [Interactive MyBinder Link](https://mybinder.org/v2/gh/unicef/giga-mlab-school-connectivity-cop/HEAD?urlpath=%2Fdoc%2Ftree%2F%2Fmaterials%2F2026-05-IQB-Edu%2Fnotebooks%2FIQB-Edu_Moldova_schools.ipynb)
- [IQB_Edu_Policy_Linkage.ipynb](./IQB_Edu_Policy_Linkage.ipynb): Exploratory notebook with sliders/GUI to test IQB-Edu scenarios - [Interactive MyBinder Link](https://mybinder.org/v2/gh/unicef/giga-mlab-school-connectivity-cop/HEAD?urlpath=%2Fdoc%2Ftree%2F%2Fmaterials%2F2026-05-IQB-Edu%2Fnotebooks%2FIQB_Edu_Policy_Linkage.ipynb)
- [pyproject.toml](./pyproject.toml) / [uv.lock](./uv.lock): Libraries and dependencies needed to run the notebooks. Run `uv sync` in this folder, then `uv run jupyter lab`.
- [iqbedu/](./iqbedu): Folder containing IQB-Edu code (wrapper code for IQB)
- [data/](./data): Files with M-Lab measurements and school metadata
