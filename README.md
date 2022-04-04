# Runnig the model in virtual environment

For the creation of virtual environments anaconda is used. [Click here](https://www.anaconda.com/distribution/) to download Anaconda

After installing anaconda into your system follow the steps bellow to work in a virtual environment.

Creation of the Virtual Enviornment:
```
conda create --name rnn_energyconsumption
```

Activating the Virtual Enviornment:
```
conda activate rnn_energyconsumption
```

Now, install all the required packages from the **requirements.txt** file to the virtual environment:
```
pip install -r requirements.txt
```

After following the above steps you can proceed to run the model in your favourite code editor supporting python.


# Time series data

The data is taken from: https://www.kaggle.com/robikscube/hourly-energy-consumption. The data is an hourly time series regarding the power consumption (in MW) in the Dayton region. The data spans from 2004-10-01 to 2018-08-03 (**n=121271**)