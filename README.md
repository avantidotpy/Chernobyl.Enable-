Visualize and Predict spread of CoronaVirus
Since the pilot out-break in Wuhan,Huebei COVID-19 has infected almost 50,000+ people in 28 countries. This project aims at visualizing changes happening on a global scale by incorporating rapid mapping of live datasets. A pilot model build upon ARIMA and Exponential Curve fitting helps to predict future outbreaks by analysing the current data pool.

<b>Getting Started</b><br>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

<b>Prerequisites</b><br>
<ol>
  <li>Python >=3.5</li>
<li>Numpy</li>
<li>Pandas</li>
<li>Statsmodels</li>
  <li>Dash</li>
<li>Amira</li>
<li>SCIPY</li>
<li>Seaborn</li>
<li>Matplotlib</li>
</ol>

Installing
A step by step series of examples that tell you how to get a development env running
<ol>
  <h3>Developing a Flask application</h3>
  <li>Fetch the CSV from this GITHUB repository:https://github.com/Perishleaf/data-visualisation-scripts<br> Data can also be imported from the repository (mapping wont be live)</li>
  <li>Create a Flask Server<br> How to set up a flash server:https://www.twilio.com/docs/usage/tutorials/how-to-set-up-your-python-and-flask-development-environment</li>
  <li>Select the plots you want to plot using the dataset<br>Guide: https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/</li>
  <li>Render the elements and the visualise the changes</li>
  <li>You can also use hello.py</li>
</ol>

<h3>TimeSeries Forecasting</h3>
<p> These models are used to forecast/predict time-series data. As our data highly depends upon timestamps it's highly advisable to use this</p>
 <ol>
  <li>It's beautifully explained how to implement any timeseries forecasting model in this link: <br>https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/</li>
  <li>Note: Make sure to use the dataset to generate the predictive model<br>If you need our model drop us a mail at <mailto>vivek.bhanushali16@siesgst.ac.in</mailto></li>
  <li> We achieved an accuracy of 97.8% with the limited dataset.</li>
  </ol>
  <p>The model uses diffrential equations to generalise results, the better the diffrential equation the higher accuracy the model yields</p>
Say what the step will be

Give the example
And repeat

until finished
End with an example of getting some data out of the system or using it for a little demo

Running the tests
Explain how to run the automated tests for this system

Break down into end to end tests
Explain what these tests test and why

Give an example
And coding style tests
Explain what these tests test and why

Give an example
Deployment
Add additional notes about how to deploy this on a live system

Built With
Dropwizard - The web framework used
Maven - Dependency Management
ROME - Used to generate RSS Feeds
Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

Versioning
We use SemVer for versioning. For the versions available, see the tags on this repository.

Authors
Billie Thompson - Initial work - PurpleBooth
See also the list of contributors who participated in this project.

License
This project is licensed under the MIT License - see the LICENSE.md file for details

Acknowledgments
Hat tip to anyone whose code was used
Inspiration
etc
