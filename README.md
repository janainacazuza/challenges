# Challenges Repository

Welcome to the **Challenges** repository, where I store and share my personal and academic projects related to **Data Engineering**, **Data Architecture**, and **Data Analysis**. This includes Kaggle challenges, FIAP challenges, and other personal data challenges I am working on.

Each challenge is organized into its own directory, containing project-specific details, datasets, and Jupyter notebooks to help you reproduce the results.

---

## Repository Structure

Here is the current structure of the repository:

```bash
challengens/                 # Main repository for data engineering and analytics challenges
├── fiap_challenge_ibovespa/ # FIAP challenge: Ibovespa closing price prediction
│   ├── data/                # Data used in the project
│   ├── environment/         # Environment setup files (requirements, environment.yml)
│   ├── notebooks/           # Jupyter notebooks for analysis and development
│   ├── storytelling/        # Storytelling materials (reports, images)
│   └── README.md            # Specific description for this challenge
├── future_challenge/        # (Example) Structure for future challenges
│   ├── data/                # Data for the new challenge
│   ├── notebooks/           # Notebooks for the new challenge
│   ├── storytelling/        # Storytelling materials for the new challenge
│   └── README.md            # Description of the new challenge
├── LICENSE                  # Repository license
└── README.md                # General repository description

```

## Current Challenges

**[FIAP Challenge - Ibovespa Closing Prediction](fiap_challenge_ibovespa/)**  
   This project aims to build a predictive model for the daily closing price of the **Ibovespa** stock index using historical data from [Investing.com](https://br.investing.com/indices/bovespa-historical-data).

The repository contains:

- Data collection and preprocessing techniques;
- Model comparison using SARIMAX, Prophet, and XGBoost;
- Model evaluation and results.

### How to Reproduce a Challenge

Each challenge has a similar structure and includes the following steps to reproduce the work:

- Clone the repository:

```bash
    git clone https://github.com/janainacazuza/challegens.git
    cd challegens
```

- Create and activate the virtual environment:

```bash
    conda create -n challenge_env python=3.9
    conda activate challenge_env
```

- Install dependencies:

```bash
    pip install -r environment/requirements.txt
    Run the Jupyter notebook for the specific challenge:
```

- Run the Jupyter notebook for the specific challenge:

```bash
    jupyter notebook notebooks/tech_challenge2.ipynb
```

- Check the final cells for results and visualizations.
  
---

## Future Challenges

This repository will continue to grow with new challenges related to:

- Data Engineering
- Data Architecture
- Machine Learning
- Data Analysis (including Kaggle competitions)
  
Check back frequently for updates and new challenges as I continue to explore different data problems and solutions.

## Contact

Feel free to reach out if you have any questions or want to collaborate:

<div>
  <a href="mailto:janainacazuza@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://www.linkedin.com/in/janainacazuza/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</div>

## License

This repository is licensed under the MIT License. See the LICENSE file for more details.