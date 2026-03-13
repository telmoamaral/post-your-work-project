# Bikeshare

The goal of the Bikeshare project is to use Python to explore data related to bike share systems. It includes one Python file and one or more .csv data files.

The project lets you analyze US bikeshare data for selected cities. You can filter the data by city, month, and day of the week, and then view insights on travel times, popular stations, trip durations, and user demographics.

## How to use this project

### Requirements and dependencies

Before running the project, make sure you have:

- Python 3.7+
- pip (Python package manager)

The install the required Python libraries using this command:

`pip install pandas numpy`

### Installation

Clone or download the project folder from your repository:

```
git clone https://github.com/your-username/bikeshare-analysis.git
cd bikeshare-analysis
```

### Running the program

To start the program, run the following command in your terminal or command prompt:

`python bikeshare_starter.py`

Then you’ll be asked to enter:

`City:`

Choose one of the following: chicago, new york city, washington.

`Month:`

Filter data by a specific month from January to June, or type all to apply no filter: january, february, march, april, may, june, all.

`Day:`

Filter by a day of the week, or type all for no day filter: monday, tuesday, wednesday, thursday, friday, saturday, sunday, all.

At the end of the analysis, you’ll be asked:

`Would you like to restart? Enter yes or no.`

Entering “yes” restarts the program; “no” exits.

### Example use cases

#### Example 1: Analyze All Data for Chicago

```
City: chicago
Month: all
Day: all
```

Output:

Displays overall statistics for all months and days available in chicago.csv.

#### Example 2: Analyze New York City in March

```
City: new york city
Month: march
Day: all
```

Output:

Shows data filtered only for March rides in New York City.

#### Example 3: Analyze Washington Data on Fridays in June

```
City: washington
Month: june
Day: friday
```

Output:

Provides insights just for Friday rides during June.

## Contribution guidelines

If you would like to contribute to this project, please contact the author at [author@server.country](mailto:author@server.country).

## Credits

This project was created to complete the ["Introduction to Version Control"](https://udacity.com/enrollment/cd0419) Udacity course. Starter code was provided by Udacity. Only the README file and minor improvements were added.

## Date created

This project and README file were created on 12th March, 2026.