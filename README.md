# Removing Clashes in TimeTables using Genetic Algorithm

## Project Description

This project aims to generate a clash-free timetable for a given set of courses and rooms using a Genetic Algorithm. The algorithm takes a timetable in CSV format as input, preprocesses the data to get the number of rooms, all courses, and all time slots, and then generates a new timetable that satisfies certain constraints, such as avoiding course clashes no section having multiple courses at the same time and no teacher having multiple classes at the same time.

## Approach

### Preprocessing
Before running the Genetic Algorithm, the script preprocesses the input timetable to get the following data:
- Number of rooms
- All courses
- All time slots

### Genetic Algorithm
The Genetic Algorithm used in this project follows these steps:
1. Generate an initial population of timetables.
2. Evaluate each timetable's fitness based on the number of constraint mismatches.
3. Select the fittest timetables for crossover and mutation.
4. Apply crossover and mutation to create a new population of timetables.
5. Evaluate each timetable's fitness again.
6. Repeat steps 3-5 for a specified number of generations or until a satisfactory timetable is found.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You will need to have Python 3.x installed on your machine. You can download the latest version of [Python](https://www.python.org/downloads/) here.

### Installing
Clone this repository onto your local machine.
```
git clone https://github.com/MuhammadAhmedSuhail/Clashless-TimeTable-using-AI.git
```
Install the required packages.
```
pip install -r requirements.txt
```

**Note**
> Make Sure to have the timetable csv in the same directory as the python program.

## Running the Program
To run the program, simply run the preprocessing Notebook first and then the Genetric Algorithm Notebook.
</br>
The Genetic algorithm will begin running to find the clashfree timetable. Once the algorithm has finished, the timetable will be saved in a csv.

## Built with:
- Python3 - Programming Language Used
- Pandas - Library used for importing/exporting and manipulating data.

## Results
The script outputs a new CSV file with the generated timetable (Timetable.csv), which is guaranteed to be clash-free. The user can then use this timetable to schedule classes.

## Author:
- Muhammad Ahmed Suhail

## Acknowledgments:
- This project was completed as an assignment for Introduction to Artificial Intelligence at FAST - NUCES Islamabad.












