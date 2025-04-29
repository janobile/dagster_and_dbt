# Dagster and dbt


# Set up local

- **To install git.** Refer to the [Git documentation](https://github.com/git-guides/install-git) if you don’t have this installed.
- **To have Python installed.**  Dagster supports Python 3.9 - 3.12.

---

## Clone the project

```bash
git clone git@github.com:janobile/dagster_and_dbt.git
```

## Install the dependencies

Create the virtual environment.

```bash
python3 -m venv .venv
```

Enter the virtual environment.

```bash
source .venv/bin/activate
```

Install the packages.

```bash
pip install -e ".[dev]"
```

## Create .env file

You will want to make a copy of the example file `.env.example` which will be used later on.

```bash
cp .env.example .env
```

## Dagster UI

To launch the UI for your project you can execute.

```bash
dagster dev
```

Open http://localhost:3000 with your browser to see the project.
