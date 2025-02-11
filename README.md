# Election Analysis

## Overview of Election Audit 
Analyze and automate the election data using [Python](https://www.python.org/doc/essays/blurb/).<br/>

### Purpose
We will have reports for: 
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout
- The total number of votes cast
- The total number of votes for each candidate
- The percentage of votes for each candidate
- The winner of the election

### Resources
- Data Resources:&nbsp; [election_results.csv](/resources/election_results.csv)<br/>
- Output File:&nbsp; [election_analysis.txt](/analysis/election_analysis.txt)<br/>
- Software:&nbsp;  [Python 3.6.1](https://www.python.org/downloads/windows/) &#44;  [Visual Studio Code 1.38.1](https://code.visualstudio.com/download)

<br/>
<b>Note:</b>&nbsp; use 'Windows x86-64 executable installer' for Python, and 'System Installer' version of VS-Code 


## Code Output in Command Line  vs   Text File

<p align="center">
  <img src="https://github.com/MousaviLaleh/Election_Analysis/blob/main/images/02.png"> _ - _ - _ - _ - _
  <img src="https://github.com/MousaviLaleh/Election_Analysis/blob/main/images/01.png">
</p>
<br/>

## Election Audit Results
The [analysis](/images/01.png) of the election show that:
- There were 369,711 votes cast in the election. 

- The counties were: 
    - Jefferson :  with 38,855 number of votes and 10.5% out of the total votes.
    - Denver    :  with 306,055 number of votes and 10.5% out of the total votes.
    - Arapahoe  :  with 24,801 number of votes and 6.7% out of the total votes.

- The candidates were:
    - Charles Casper Stockham :  with 85,213 number of votes and 23.0% of the vote.
    - Diana DeGette           :  with 272,892 number of votes and 73.8% of the vote.
    - Raymon Anthony Doane    :  with 11,606 number of votes and 3.1% of the vote.

- **Denver** county had the largest number of votes.

- **The winner** of the election was:
    - Candidate **Diana DeGette**, who received **73.8%** of the vote and **272,892** number of votes.
<br/>


## Election Audit Summary
Using a programming language like Python, and writing scripts in Python has many advantages like automating processes, fast execution of the code, and reusing the code for similar projects. <br/>
This code quickly returns numerous data for a U.S. Congressional Precinct in Colorado, but can be easily used but for other elections as well. This code will automatically :
- find candidates names,
- find counties,
- count votes for each candidate and calculate vote percentage,
- count turnout per county and calculate their percentage,
- declare a candidate winner base on the highest vote count and percentage,
- declare a county with the highest turnout.

This code can be used on similar projects such as other congressional district elections, senatorial districts, local elections, and more.<br/>

- Since Python script finds unique names of candidates and counties we can reuse this code on a much larger dataset with more candidates, more counties or other areas.
- This code reads csv files but can be easily converted to read other files such as json, by importing other dependencies to the code, for example *import json*.<br/><br/>
![03.png](/images/03.png) <br/><br/>
- This code accesses the dataset in a specific directory and writes a report to a specific file, but this specific lines of codes can be easily fixed by renaming a directory and file in the code itself.<br/><br/>
![04.png](/images/04.png) <br/><br/>
- This code reads candidate name on 2nd index and county on 1st index, but in case of a different structure of the data set this lines of codes can be easily converted. <br/><br/>
![05.png](/images/05.png)<br/>
<br/>


