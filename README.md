# Song Lyrics Analysis

The repo is for the project SMU IS425 Text Mining, Song Lyrics Analysis

## Project Structure

```
    validation, etc.
    ├── datasets                 <- Inputs/Outputs data for analyics/modeling in offline mode. 
    │   ├── raw                   <- The original/raw input data
    │   ├── interim               <- Intermediate output data that has been transformed
    │   ├── processed             <- The final ouput
    │   ├── reports               <- The analytics/modeling reports (excel, html,, pdf, html, figures etc)
    ├── docs                 <- References documents for the project, data dictionaries, manuals, etc.      
    ├── envs                 <- Environment for the project 
    ├── notebooks            <- Jupyter notebooks
    │   ├── preprocessing.ipynb            <- for preprocessing data scraped from scraper
    │   ├── scraper.ipynb                  <- match song lyrics with 
    ├── .gitignore           <- Files/dir to be ignored during check-in to github
    ├── LICENSE              <- The license file for the project
    ├── README.md            <- The top-level README for DA/DS/DE/ML using this project. 
    ├── requirements.txt     <- The requirements file for reproducing the working environment --> pip    
```

## Initial SetUp

1. Clone & Go to the Repo

  ```bash
  git clone $URL
  ```

  ```bash
  cd $project_name
  ```

1. Download spaCy
  
- Follow [spaCy installation](https://spacy.io/usage)
