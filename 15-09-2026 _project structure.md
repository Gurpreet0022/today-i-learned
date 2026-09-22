Always create separate .env files foe dev, test and prod. 

# Here's sample project structure

pii_nonpii_project/
│
├── .env
│
├── notebooks/
│   └── xxxxName.ipynb
│
├── config/
│   ├── .env.dev
│   ├── .env.test
│   └── .env.prod
│
├── queries/
│   ├── xxxTable/
│   │   ├── xxxQuery.sql
│
├── src/
│   ├── db.py
│   └── config.py
│
└── data/
    ├── input/
    └── output/