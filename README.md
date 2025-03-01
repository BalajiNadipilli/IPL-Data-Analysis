# IPL-Data-Analysis
This repository contains a Python program for analyzing IPL (Indian Premier League) player statistics. The dataset includes player salary, games played, and points earned over multiple seasons. The analysis aims to provide insights into how different players perform in the IPL season by visualizing trends in player salaries, games, and points.

**Project Structure:**
      -ipl_data_analysis.ipynb: A Jupyter Notebook that contains the code to analyze the IPL dataset, visualize trends, and perform data manipulation using numpy and matplotlib.
      -data/: Directory to store any necessary data files (for future additions).
      -images/: Directory to store any visualizations (plots) generated during the analysis.

**Features:**
      -Player Salaries: The notebook analyzes and visualizes the salaries of players across different seasons of IPL.
      -Games Played: Tracks the number of games played by each player across multiple IPL seasons.
      -Points Earned: Analyzes the points earned by players over multiple seasons and compares them.
      -Visualization: The project uses Matplotlib to generate various line plots to visualize player performance over seasons, including salary, games, and points.

**Key Components:**
  1.Data Preparation:
      The dataset is structured as numpy arrays containing salary, games played, and points earned by players in each season.
    Arrays are reshaped and manipulated to analyze data efficiently.

  2.Visualization:
      -Line Plots: The salary of each player over the seasons is visualized with various styles, including different colors, markers, and line styles.
      -Multiple Players' Performance: Performance (salary) for multiple players is plotted on the same graph for comparison.

  3.Dictionary Usage:
             -A dictionary maps players' names to indices for easier data management and access.

  4.Data Analysis:
            -The program reshapes and prints various matrices and uses the data for plotting comparisons between players.

**Usage:**
      1.The notebook contains Python code that loads the IPL player statistics into numpy arrays and analyzes them.
      2.Visualize player salaries over time using Matplotlib plots.
      3.Perform data reshaping and manipulation with numpy.
      4.View the comparative performance of players through line plots.

**Example of generating a plot for player salaries:**
      plt.plot(Salary[0], c='Green', ls='--', marker='s', ms=7, label=Players[0])
      plt.show()

**Outputs:**
      -The notebook will output various plots that show how players' salaries, games, and points have changed across the years of the IPL seasons.
      -Each player’s performance is shown with a different color and marker for easy comparison.

**Example Visualization:**
      plt.plot(Salary[0], c='Green', ls='--', marker='s', ms=7, label='Sachin')
      plt.plot(Salary[1], c='Blue', ls='--', marker='o', ms=7, label='Rahul')
      plt.legend(loc='lower right', bbox_to_anchor=(0.5,1))
      plt.show()

