# Basic Install & Setup for DBT #
This walks through setting up a virtual environment, DBT installation, and empty project initialization on Windows. Ensure you have python 3.6 or newer and OpenSSL installed, added to path, and the appropriate environment variables set (see Getting Started | OpenSSL).

## Create virtual Environment ##
`python -m venv .venv`

`.\.venv\Scripts\Activate.ps1`

## Clone DBT repo and install ##
`git clone https://github.com/fishtown-analytics/dbt.git`

`cd dbt`

`pip install -r requirements.txt`

`cd ../`

### Optional - Remove DBT repo ###
`rm -Force -Recurse dbt`

## Initialize empty DBT project ##
`dbt init my-project-name`

*Where `my-project-name` is whatever name you choose*