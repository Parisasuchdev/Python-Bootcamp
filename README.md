# Python Bootcamp

This short bootcamp is designed to help you move from basic Python syntax to practical data analysis and web scraping using Jupyter Notebooks inside Visual Studio Code.

You will:
- Learn basic python concepts
- Set up a working Python environment with Anaconda and Conda
- Work inside Jupyter Notebooks using VS Code
- Explore real-world datasets using pandas
- (Optional) Learn how to scrape data from websites using BeautifulSoup

By the end, you’ll have working notebooks demonstrating your ability to analyze and collect data programmatically.

Here is the link to full [playlist](https://www.youtube.com/watch?v=xi0vhXFPegw&list=PLu7Hcqy8NmKzGnIc3T9c3-GHvdZocRdes)

Note: if Windows users fall into some error, it could be related to PATH Environment Variables, this link is helpful to debug those | [Watch](https://www.youtube.com/watch?v=OdIHeg4jj2c&list=PLu7Hcqy8NmKwv7Lw762dFzoSXqj3MwBsh&index=25)

---

## Learning Steps

| Step | Title | Description | Link |
|------|-------|-------------|------|
| 1 | Installing Visual Studio Code | Set up VS Code for Python development on Mac and Windows | [Watch](https://www.youtube.com/watch?v=wx391N_MEgI&list=PLu7Hcqy8NmKzGnIc3T9c3-GHvdZocRdes&index=1) |
| 2 | Python Full Course for Beginners | Review core Python concepts: variables, conditionals, loops, functions | [Watch](https://www.youtube.com/watch?v=K5KVEU3aaeQ&list=PLu7Hcqy8NmKzGnIc3T9c3-GHvdZocRdes&index=2) |
| 3 | Setup Jupyter in VS Code | Learn how to launch and use Jupyter Notebooks inside VS Code | [Watch](https://www.youtube.com/watch?v=K0B2P1Zpdqs&list=PLu7Hcqy8NmKzGnIc3T9c3-GHvdZocRdes&index=3) |
| 4 | Library and Dataset Setup | Follow the instructions below to install required libraries and download the dataset | — |
| 5 | Exploratory Data Analysis with Pandas (Project!) | Perform data analysis and visualization using pandas, matplotlib, seaborn | [Watch](https://www.youtube.com/watch?v=xi0vhXFPegw&list=PLu7Hcqy8NmKzGnIc3T9c3-GHvdZocRdes&index=4) |
| 6 | Web Scraping with BeautifulSoup | Scrape structured data from real websites and save to CSV | [Watch](https://www.youtube.com/watch?v=8dTpNajxaH0&list=PLu7Hcqy8NmKzGnIc3T9c3-GHvdZocRdes&index=5) |

---

## Environment Setup Instructions

Before starting step 4:  
After setting up Jupyter in VS Code, make sure you know how to:

- Create `.ipynb` notebook files
- Select a Conda kernel
- Open the integrated terminal in VS Code

### 1. Install Required Libraries

Open the terminal in VS Code, then run the following command:

```bash
conda install jupyter pandas numpy matplotlib seaborn beautifulsoup4 -y
```

This installs the required libraries used in steps 5 and 6.
The -y flag automatically confirms the installation without prompting.

### 2. Download Dataset from This Repository

The dataset (e.g., `rollercoasters.csv`) is stored in this GitHub repository, follow these steps to download it:

1. Navigate to the file in the GitHub repo (e.g., `rollercoasters.csv`) or click [here](https://github.com/Parisasuchdev/Python-Bootcamp/blob/main/coaster_db.csv)
2. Click on the file to open it
3. Locate the **“Download raw”** icon on the right
4. Make sure the file extension is .csv
5. Save it to the same directory where your notebook is located

Follow steps 5 and 6.

## Resources of further learning

For a whirlwind tour of some of Python's essential syntax and semantics, built-in data types and structures, function definitions, control flow statements, and other aspects of the language, refer to this [Handbook](https://nbviewer.org/github/bagrow/WhirlwindTourOfPython/blob/master/01-Introduction.ipynb).

For additional resources, visit [Further Learning](https://nbviewer.org/github/bagrow/WhirlwindTourOfPython/blob/master/18-Further-Resources.ipynb).

Have fun!

Contact Cailin or Parisa if additional help is needed.

--
## Credits

The following YouTube creators produced the tutorials referenced in this guide. All rights and content belong to their respective creators:

- [The Common Coder](https://www.youtube.com/@thecommoncoder) – *Installing Visual Studio Code on Mac and Windows*
- [Programming with Mosh](https://www.youtube.com/@programmingwithmosh) – *Python Full Course for Beginners*
- [ProgrammingKnowledge](https://www.youtube.com/@ProgrammingKnowledge) – *How to Setup & Run Jupyter Notebooks in VS Code*
- [Rob Mulla](https://www.youtube.com/@robmulla) – *Exploratory Data Analysis with Pandas*
- [Alex The Analyst](https://www.youtube.com/@AlexTheAnalyst) – *Web Scraping with BeautifulSoup*
- [Corey Schafer](https://www.youtube.com/@Coreyms) – *Setting the PATH and Managing Python Versions on Windows*

# Python-Bootcamp
