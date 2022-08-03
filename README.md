# PassiveInvestingWithETF

## Description

The Passive Investing with ETF notebook is a sample notebook that illustrates how to access a financial database using SQL and to deploy the notebook as a web application. In this example, we are provided with a test database `etf.db` that contains OHLCV data for the following stocks: GDOT, GS, PYPL, SQ. With this data, we perform the following steps:

1. Analyze a single asset in the ETF
2. Optimize data access with Advanced SQL queries
3. Analyze the ETF portfolio
4. Deploy the notebook as a web application

## Technologies

This example uses the following technologies:

- **Jupyter** - Jupyter is a web-based interactive development environment for data science and analysis. Please see [Jupyter documentation](https://jupyter.org/) for more information.
- **pandas** - pandas is a software library written for the Python programming language for data manipulation and analysis. Please see [pandas documentation](https://pandas.pydata.org/) for more information.
- SQLAlchemy - SQLAlchemy is an open-source SQL toolkit and ORM for Python. Please see [SQLAlchemy documentation](https://www.sqlalchemy.org/) for more information.
- Voilà - Voilà is a python library that turns Jupyter notebooks into standalone web applications.

## Installation

In order to use this application, you will need to install `Jupyter`, `pandas`, `hvPlot`, `SQLAlchemy` and `Voila`. Below are the instructions for installing each required library.

### Installing Jupyter

To install Jupyter, please refer to the [Jupyter Installation Guide](https://jupyter.org/install).

### Installing pandas

To install `pandas`, please refer to the [pandas Installation Guide](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html).

### Installing SQLAlchemy

To install `sqlalchemy`, please refer to the [SQLAlchemy Installation Guide](https://pypi.org/project/SQLAlchemy/).

### Installing Voila

To install `Voila`, please refer to the [Voila Installation Guide ](https://pypi.org/project/voila/).

## Usage

### Launching the Notebook

To launch the Notebook, perform the following steps:

1. Open Terminal.

![Launch_Terminal](/Images/launching_open_terminal.jpg)

2. Navigate to the location of the Notebook.
3. Enter `jupyter lab` at the Terminal prompt.

![Launch Jupyter](/Images/launching_jupyter.jpg)

4. Verify that you can access Jupyter in your browser.

![Jupyter](/Images/jupyter.jpg)

Once you have launched the notebook, you can then execute each section.

- Analyze a single asset in the ETF
- Optimize data access with Advanced SQL queries
- Analyze the ETF portfolio

### Deploy the Notebook as a Web Application

To deploy the notebook as a web application, do the following:

1. Launch the terminal.

![Launch_Terminal_Voila](/Images/voila_terminal.jpg)

2. Enter in the following command to deploy the notebook with Voila:

`(base) quinnwong@Quinns-MBP PassiveInvestingWithETF % voila etf_analyzer.ipynb`

This will start the Voila web server:

![Voila Start Server](/Images/voila_start_server.jpg)

3. Verify that the notebook has launched as a web application:

![Launch Voila](/Images/voila_intro.jpg)

![Voila Step 3](/Images/voila_step3.jpg)

## Contributors

This sample application was authored by:

Quinn Wong (quinn.wong@gmail.com)
LinkedIn: https://www.linkedin.com/in/quinnwong/

## License

The MIT License (MIT)

Copyright (c) 2022 Quinn Wong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
