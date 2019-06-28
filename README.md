# Intro
You will be parsing and analyzing hourly weather data from Hartsfield-Jackson Airport and Canadian, TX.

# Provided
Attached are two CSV files with hourly weather data for Hartsfield-Jackson Airport and Canadian, TX.
Also included is the Local Climatological Data (LCD) Dataset Documentation, which contains definitions of weather codes within the data set.

# Instructions
Please select one of the following languages with which to complete the test. If you would like to use a different language, feel free to ask us.

- C
- C#
- C++
- Go
- Java
- JavaScript
- Python
- Rust

Include a `README_solution.txt` file which includes the following:

- which version of the language you are using. Ensure you do not use platform-specific features as your solution may be tested on Mac, Linux, or Windows.
- a short paragraph justifying or explaining your language choice.
- any instructions necessary for running your code.

Note: PLEASE DO NOT INCLUDE YOUR NAME IN THE README OR CODE!

Read the data as input and write three methods:

1. a method that takes a data set and a date as its arguments and returns a data structure with the average and sample standard deviation of the Fahrenheit dry-bulb temperature between the times of sunrise and sunset.
2. a method that takes a data set and a date as its arguments and returns the wind chills rounded to the nearest integer for the times when the temperature is less than or equal to 40 degrees Fahrenheit.
3. a method that reads both data sets and finds the day in which the conditions in Canadian, TX, were most similar to Atlanta's Hartsfield-Jackson Airport.
You may use any column(s) for your similarity metric, but be prepared to justify your choice of measurements.

# Submission
Please submit a `.zip` or `.tar.gz` archive named `CIPHER_weather_test` containing the following:
- `README_solution.txt`
- The included CSV datafiles
- Your source code and any scripts or build files needed to execute your code.

Please do NOT include:
- Your name anywhere in the submission or filenames.
- Bytecode, machine code, or non-source code.
