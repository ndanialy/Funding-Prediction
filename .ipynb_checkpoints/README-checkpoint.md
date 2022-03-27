# Funding Prediction
 An app that uses a neural network to predict whether an applicant's business will be successful.

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate the csv files.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

* [numpy](https://numpy.org/doc/) for certain numericalfunctions.

* [sklearn](https://scikit-learn.org/stable/user_guide.html) for the logistical regression.

* [tensorflow](https://www.tensorflow.org/api_docs/) for the neural network calculations.
---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab

pip install python-dotenv

pip install sklearn

pip install tensorflow

```
---

## Usage

The App imports data from the csv in the resources file, and processes it for the neural network it by encoding the categorical variables:

![encoding](https://user-images.githubusercontent.com/96391748/160266658-02c4940d-3f9c-4847-8ec3-5aa6b7ac60cf.PNG)

A neural network is then created and the data is fitted to the data before it is run:

![neural_network](https://user-images.githubusercontent.com/96391748/160266687-ba99c298-ea80-4fbe-8c97-b49ec1ddfe9a.PNG)

The results of the model are then processed and displayed:

![evaluation](https://user-images.githubusercontent.com/96391748/160266703-13a648ac-923f-4848-9267-f129a3a750d6.PNG)

Finally, two alternate models are created in an attempt to improve the model, the results of which are evaluated and displayed as well:

![alternate_results](https://user-images.githubusercontent.com/96391748/160266726-8fe9a697-f475-4615-a77f-01bad98e9908.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE