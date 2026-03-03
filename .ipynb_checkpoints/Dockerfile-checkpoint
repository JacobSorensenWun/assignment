# Use the official Jupyter Scipy image (includes pandas, numpy, etc.)
FROM quay.io/jupyter/scipy-notebook:latest

# Install DuckDB and SQL magic tools
# jupysql: allows %%sql cells
# duckdb-engine: the SQLAlchemy driver for duckdb
RUN pip install --no-cache-dir \
    duckdb \
    duckdb-engine \
    jupysql

# (Optional) Pre-create a workspace directory
WORKDIR /home/jovyan/
