# CSE 4099: Capstone Project
## by Divij Kulshrestha [17BCE2116] and Mohith J [17BCE2135]

This repo contains Python code for the web application we built for our capstone project in our final semester at VIT. This project is now hosted on the Streamlit Community Cloud - [BreatheEasy](https://breathe-easy.streamlit.app/)

**As of April 2024, this project is facing a bug in unpickling the ML models used for each city. This is due to a mismatch in the sci-kit learn library and is currently being looked into. The sklearn library is also deprecated as of 1 Dec, 2023.

For more information about this open issue, check out these threads:
1. [ValueError Due to Incompatible DTYPE](https://discuss.streamlit.io/t/valueerror-node-array-from-the-pickle-has-an-incompatible-dtype/46682)
2. [Open Thread Raised on Forums](https://discuss.streamlit.io/t/streamlit-cloud-installs-wrong-version-of-library/68012)
3. [StackOverflow Thread](https://stackoverflow.com/questions/78341395/exception-type-valueerror-node-array-from-the-pickle-has-an-incompatible-dtype)

# Aim
Our project aims to use machine learning to forecast the level of pollution (specifically, PM 2.5 values) for vairous urban Indian cities using publicly available pollution and meteorological data from [OpenWeather](https://openweathermap.org/), the Central Pollution Control Board website, and the [Reliable Prognosis Weather Archive](https://rp5.ru).

The web app was built in Python using the following libraries:

    * streamlit
    * pandas
    * numpy
    * scikit-learn
    * xgboost
    * requests
    * pytz
    * pickle
