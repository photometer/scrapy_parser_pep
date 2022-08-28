# Asyncronous PEP parser project

[PEP documents](https://www.peps.python.org/) parser based on Scrapy 
framework.

Parser loads collected information into csv-files:
- `pep_{datetime}.csv` contains list of all PEPs: number, name and status.

- `status_summary_{datetime}.csv` contains summary on all PEPs — every status 
count and total count of all documents.


## Techologies:
- Python
- Scrapy
- SQLAlchemy

## Project installation and launch (on Windows)
- Clone the repository on your PC:

```bash
git clone git@github.com:photometer/scrapy_parser_pep.git
```

- Create and activate virtual environment in project folder:

```bash
python -m venv venv
. venv/scripts/activate
```

- Install requirements from `requirements.txt` file:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

- Parser launch:

```bash
scrapy crawl pep
```

## Author
Liza Androsova :star:
