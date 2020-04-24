# bold-strategy-cotton

Final project for UNC Data Viz, using machine learning to predict the success of college football players in the Draft and the NFL

Drafting Success: Using Machine Learning to Identify Star Players in the 2020 NFL Draft 
A report brought to you by BOLD STRATEGY COTTON
Jimmy Brawner, Michael Hargroder, Nathan Kosiba, Chris Marchini

If you have seen Moneyball, there is a great scene where talent scouts pontificated on what players to draft based on gut instincts while Brad Pitt and Jonah Hill drafted players based on statistics. This illuminated a key issue when making a choice: what data will best inform our decision making for success? 

Now consider NFL draft picks. Every year, NFL teams have a plethora of college athletes to choose from. Some top college players that seem like solid picks may end up being duds, while other lower picks may become a star player. So, what makes a future star player with a great performance record? What variables matter and can help teams make better investments in players? 

Using a set of pre-determined criteria, our data will be sorted into players who had either "successful" NFL careers or "unsuccessful" careers. Using this data pool, we will teach the model to identify what characteristics are common for "successful" players, and what characteristics are common for "unsuccessful" ones. The data that the model will be trained on will include college career statistics, NFL combine results, biophysical data, and some personal data. Once we have taught the model to identify "successful" players, we will apply it to the 2020 NFL draft class to try to predict player success for their NFL careers.

We anticipate needing to do scrape data from the web using tools such as Splinter, Beautiful Soup, and/or Pandas. We will clean and consolidate our data using Jupyter Notebooks either in Pandas or Colaboratory, store our data in a SQL database, and use TensorFlow to train our models. As a point of comparison, we will see if our model would predict players that are current successful to see how accurate it will be. 
To display our data, we will us JavaScript code to help develop a dynamic front-end application using HTML, CSS, and Bootstrap. 
