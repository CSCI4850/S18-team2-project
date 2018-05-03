# Predicting Bitcoin Price Using Recurrent Neural Networks with Long Short-Term Memory

This project uses a Recurrent Neural Network, specifically an LSTM, to predict future prices of the cryptocurrency Bitcoin. It uses 4 years of previous minutely Bitcoin pricing data obtained from kaggle.com that is then resampled into a daily price, mean-centered, and then min-max scaled. The network is able to predict general trends in the price of Bitcoin but extensive future work is required. The model currently behaves as a regressor more than anything else.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Your machine needs to have the following installed for this project:
1. Python 3.3 or better. This is required to run the Jupyter Notebook. You can find the latest version on https://www.python.org/downloads/

2. Jupyter Notebook. The source file including the demo is written in the Jupyter Notebook. You can find instructions on how to install Jupyter Notebook at https://jupyter.org/install

3. TensorFlow. This is required for Keras. You can find instructions on how to install at https://www.tensorflow.org/install/

4. Keras. This project used keras libraries. You can find instructions on how to install at https://keras.io/#installation

5. Pandas. Pandas is a required package for loading and preprocessing of the data. You can find instructions on how to install at https://pandas.pydata.org/pandas-docs/stable/install.html

6. Sklearn. This package is needed for the plotting of the graph and progress bar while learning. You can find instructions on how to install at http://scikit-learn.org/stable/install.html

### Installing

Once you have your environment ready. You can clone the project

From command line with this command:
```
$ git clone git@github.com:CSCI4850/S18-team2-project.git
```

## Demo
You can find a demo of the project in the subdirector "Demo". There should be two files in there. The first will be an python Jupyter Notebook(.ipynb) that includes the source code of the demo with explanation, and the second will be a sample data (.csv) required for the demo.

To run a script in jupter notbook, you need to press "Shift + Enter" in the specified cell. For example if to run "Hello World!", you need to write the script in the cell like:
![alt text](/image/print.jpg)
But it won't be executed until the "Shift + Enter(Return)". After execution it should look something like this:
![alt text](/image/print2.jpg) This is important to remember when going through the demo. If you only press "Enter(Return)" it will start a new line within the same cell.

**You need to satisfy the [prerequisites](#Prerequisites) to avoid any errors while running the demo.**

## Authors

* **Bishoy Boktor**
* **Yonathan Feleke**
* **Ryan Florida**
* **Kyle Lutz**
* **Joel Norris**
* **Karla Robles**

## License

This project is licensed under the MIT License.
