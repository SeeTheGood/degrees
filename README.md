Six Degrees of Kevin Bacon

This repository contains a Python script for determining the degrees of separation between two actors using the Six Degrees of Kevin Bacon concept.

Overview
The script loads data from CSV files containing information about people, movies, and their connections. It then uses a breadth-first search algorithm to find the shortest path between two given actors, measuring their degrees of separation based on shared movies.

Features
Data Loading: Loads data from CSV files into memory, including information about people, movies, and their connections.
Shortest Path Calculation: Implements a breadth-first search algorithm to find the shortest path between two actors.
Degrees of Separation: Determines the number of degrees of separation between two actors based on the movies they have starred in.
User Interaction: Prompts the user to input the names of the two actors to find their degrees of separation.
Usage

To run the script, execute it in a Python environment:python degrees.py

If no directory is specified, it defaults to "large". The script will then prompt the user to input the names of the two actors to find their degrees of separation.

File Structure
people.csv: Contains information about people, including their names, birthdates, and movies they have starred in.
movies.csv: Contains information about movies, including their titles, release years, and actors.
stars.csv: Contains information about the connections between people and movies, indicating which actors starred in which movies.
