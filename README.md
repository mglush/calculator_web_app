# Simple Calculator Web App Server.
#### By Michael Glushchenko, using [this](https://www.youtube.com/watch?v=X7sl1cHN_Nc&ab_channel=RezaArjmandi) tutorial.

## How To Run
1) Clone the git repository, and cd into it.

'''
git clone git@github.com:mglush/calculator_web_app.git
cd calculator_web_app
'''

2) Compile and run the backend API.

'''
cmake -Hcalculator_backend -Bcalculator_backend/build
cmake --build calculator_backend/build --target all --config Release
calculator_backend/build/CalculatorAPI
'''

3) Open a NEW terminal window, and start the frontend.

'''
cd calculator_frontend
npm start
'''

If a window does not open automatically within your browser, you can access the calculator web app at http://localhost:3000 or http://127.0.0.1:3000

## Technologies Used
Front-end: React, Javascript, CSS.<br />
Back-end: C++.<br />
Build: Cmake.<br />
Web API Framework: Restbed.<br />

## Purpose
The first step in an attempt to build a more complex full-stack web app later on.
