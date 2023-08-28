
# Real Madrid UEFA Champions League Performance Analysis
### A Comprehensive Study by a Senior Data Scientist and Game Theorist

## Introduction
In the high-stakes world of professional football, public opinion often forms around emotions, loyalties, and subjective interpretations. The project at hand aims to transcend these biases by delving into a robust, data-driven analysis of Real Madrid's performance in the UEFA Champions League over the past decade.

Through a blend of traditional statistical methods, machine learning models, game theory, psychology, philosophy, and even military strategies, this investigation presents a multifaceted view of what contributes to a football team's success and how performance can be objectively evaluated.

## Exploratory Data Analysis (EDA)
The EDA consists of two layers:

### 1. Statistical Analysis:
* **Set-Up Process:** Loading libraries, data frames, determining position relevancy, and calculating average minutes played.
* **Kurtosis:** Understanding data variance and its internal behavior.
* **Feature Engineering:** Preprocessing with standard scaler for later ML applications.
* **Sample Statistics, Distribution, and Standard Errors:** Essential for inference.
* **Central Limit Theorem:** A focus for understanding by experienced data scientists.
* **A/B Testing & ANOVA:** Used for null hypothesis testing.

### 2. Machine Learning Models:
* **Ordinary Least Square:** To estimate the unknown parameters.
* **Linear Regression Models with Sci-Kit Learn:** Predicting the dependent variable.
* **XGBoost & Cross-Validation:** A powerful algorithm for making predictions.
* **Conformal Prediction:** To create valid prediction regions.
* **Radar Maps:** For visualizing player performance during their match campaigns.

## Objectives
The goal of this analysis is multifaceted:
1. **Unveil Hidden Statistics:** To reveal the underlying patterns often overlooked in casual discussions.
2. **Demonstrate the Impact of Probability:** How it shapes matches and seasons.
3. **Explore Interdisciplinary Influences:** Including Game Theory, Strategy, Cooperation, Psychology, Physiology, Military Training, Luck, Economics, Philosophy, and even Freudian Analysis.
4. **Challenge Subjective Bias:** By presenting a well-rounded, evidence-based view of football performance.

## Conclusion
This project stands as a testament to the profound complexity of football performance and the nuanced insights that can be derived through rigorous scientific analysis. Whether a data scientist recruiter, football fanatic, or curious mind, the findings herein offer a unique perspective that bridges the gap between passion and empiricism.

## Contact Information
For further inquiries, collaboration, or access to the project, please find the contact information on my [GitHub](https://github.com/joakor89/Real-Madrid-Luck) and [Kaggle](https://www.kaggle.com/joaquinaromerof) profiles.


# Virtual Environment
The following commands are used to set up a virtual environment for your project. 
This helps isolate dependencies and create a consistent development space.

```sh
pip install --upgrade pip                 # Upgrade pip to the latest version
python3 -m pip install virtualenv          # Install virtual environment package
python3 -m venv env                        # Create a virtual environment named 'env'
source env/bin/activate                    # Activate the virtual environment
source env/bin/deactivate                  # Deactivate the virtual environment
pip3 install -r requirements.txt           # Install required packages from a text file
```

# Github Environment
#### Performed from Terminal Console

These commands are used to initialize a new Git repository, link it to a remote GitHub repository,
stage changes, commit them, and then push them to the master branch.
```sh
1. git init                                # Initialize a new Git repository
2. git remote add origin ["URL"]           # Link to the remote repository
3. git remote -v                           # Verify the remote URL
4. git add -A                              # Stage all changes
5. git add .                               # Alternative command to stage changes
6. git commit -m "message"                 # Commit staged changes with a message
7. git status                              # Check the status of the repository
8. git push origin master                  # Push changes to the master branch
```

### Additional GitHub Commands
These commands are used if you're working with an existing repository and
include steps to properly synchronize your local copy with the remote version.
```sh
1. git remote add origin ["URL"]           # Link to the existing remote repository
2. (Follow the same procedure as above)    # Follow previous steps for staging and committing
3. Note: Always pull before push.          # Recommended practice to pull before pushing
4. git push origin master                  # Push changes to the master branch
```

### Scrapy Environment
The following commands are used to set up a Scrapy project for web scraping. 
Scrapy is a popular framework for extracting data from websites.
```sh
1. Create folder - (mkdir folder_name)     # Create a directory for the project
2. Initialize repository (git init)        # Initialize a Git repository
3. Create gitignore - (touch .gitignore)   # Create a .gitignore file
4. Open folder_name in VSC                 # Open the folder in Visual Studio Code
5. Activate environment                    # Activate the previously created virtual environment
6. Install dependencies - (pip install scrapy autopep8) # Install Scrapy and autopep8
7. Verify Scrapy - (scrapy version)        # Verify that Scrapy is installed correctly
8. Create the project - (scrapy startproject folder_name) # Start a new Scrapy project
9. Enter the folder - (cd folder_name)     # Navigate into the project directory
```

## Disclaimer for Scrape Environment: Educational and Consultancy Purpose

#### Understanding Social Engineering
Social Engineering is the psychological manipulation of individuals to disclose confidential information. It's an art that leverages human interaction to deceive and influence individuals, leading them to reveal sensitive details such as passwords or financial information. In our interconnected digital world, Social Engineering is an increasingly prevalent concern in cybersecurity.

#### Purpose of the Scrapy Environment
The Scrapy environment and procedures detailed in this project are provided exclusively for educational, literacy, and consultancy purposes. They serve to illustrate methodologies, tools, and techniques within legal and ethical boundaries.

#### Disclaimer:
Please observe the following principles when engaging with this content:
1. **Legitimate Use:** Utilize the scraping techniques provided here only for lawful purposes and with proper authorization.
2. **Ethical Conduct:** Uphold the values of responsibility and ethics in data science and informatics.
3. **Educational Intent:** Approach the content as a learning tool, aimed at raising awareness about Social Engineering and promoting ethical practices.

**Please Note:**
The scraping methods are designed to foster understanding of data acquisition techniques. Under no circumstances are they to be used for unauthorized or malicious intent.

#### The Impact of Social Engineering Today:
Social Engineering's effectiveness lies in its exploitation of human behavior rather than technological weaknesses. Understanding its principles is vital to cybersecurity, illuminating the need for awareness, caution, and ethical conduct in our digital interactions.

This project serves as a testament to the nuanced relationship between data science, human psychology, and game theory. It underscores the importance of mindful practice, continuous learning, and ethical commitment in navigating the complex digital landscape.

Certainly! Below are the references formatted according to the APA convention, suitable for inclusion in your README.md file and the bibliography page of your intelligence analysis.

## References

- Nimon-Peter, A. (Year). *Working with Influence*. Bloomsbury Business. ISBN 978-1-4729-8873-7
- Bruce, P., Bruce, A., & Gedeck, P. (Year). *Practical Statistics for Data Scientists*. O'reilly. ISBN 978-1-492-07294-2
- Géron, A. (Year). *Hands-on Machine Learning with Scikit-Learn, Keras & TensorFlow* (2nd ed.). O'reilly. ISBN 978-1-492-03264-9
- Wasserman, L. (Year). *All of Statistics - A Concise Course in Statistical Inference*. Springer Editorial. ISBN 978-1-4419-2322-6
- Tadelis, S. (Year). *Game Theory - An Introduction*. press.princeton.edu. ISBN 978-0-691-12908-2
- Rovira, A., & Trías de Bes, F. (Year). *La Buena Suerte*. Zenith Libros. ISBN 9-788408-216032
- James, G., Witten, D., Hastie, T., & Tibshirani, R. (Year). *An Introduction to Statistical Learning with Applications in R* (2nd ed.). Springer Editorial. ISBN 978-1-0716-1417-4
- Harrison, M. (Year). *Effective XGBoost - Tuning, Understanding & Deploying Classification Models*. Metasnake. ISBN 9798387967726
- Wade, C. (Year). *Hands-On Gradient Boosting with XGBoost and Scikit-Learn*. Packt. ISBN 978-1-83921-835-4
- Owen, L. (Year). *Hyperparameter Tuning with Python*. Packt. ISBN 978-1-80323-587-5
- Dixit, A. K., & Nalebuff, B. J. (Year). *Thinking Strategically - The competitive edge in Business, Politics, and Everyday Life*. WWNorton. ISBN 978-0-393-31035-1
- Axelrod, R. (Year). *The Evolution of Cooperation* (Revised ed.). Basic Books. ISBN-13 978-0-465-00564-2
- Grossman, D. (2004). *On Killing* (Spanish ed.). Editorial Melusina. ISBN-10: 8415373694
- Grossman, D. (2014). *On Combat* (Spanish ed.). Editorial Melusina. ISBN-13: 978-8415373155
- Freud, S. (Year). *Jenseits des Lustprinzips (Beyond the Pleasure Principle)* (Spanish ed.). Akal. ISBN-10: 8446049155
- Kuper, S., & Szymanski, S. (2018). *Soccernomics*. Bold Type Books. ISBN-13: 978-1568587516
