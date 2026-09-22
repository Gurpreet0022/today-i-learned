1. Organize your project into folders , subfolders depending on your project. 

Here's example of project structure:

pii_nonpii_project/
│
├── .env
│
├── notebooks/
│   └── xxxxName.ipynb
│
├── config/
│   ├── .env.dev
│   ├── .env.test
│   └── .env.prod
│
├── queries/
│   ├── xxxTable/
│   │   ├── xxxQuery.sql
│
├── src/
│   ├── db.py
│   └── config.py
│
└── data/
    ├── input/
    └── output