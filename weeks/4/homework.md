# Due by Wednesday, Feb 5th, 1:00 PM

## Preparation

1. Go to https://github.com/kiei925-winter14/week4-homework
1. Fork the repository into your own account.
1. Clone your new repository down to your laptop.
1. Open the code in Sublime Text.
1. Using your command prompt:
  1. Use the `cd` command to change to your app's directory
  1. Run the command: `bundle install`
  1. Run the command: `rails server`
1. Browse to `http://localhost:3000` and you should see a nice Bootstrapped welcome page, with a reminder of the homework instructions built in!

## Tasks
1. Replicate what we built in class:
  1. "http://localhost:3000/weather/search" should display a form I can use to enter a city name
  1. "http://localhost:3000/weather/conditions" should display the city name and at least one weather condition (temperature, wind speed, humidity, etc.)
  1. Remember, you can use a web service like http://www.openweathermap.org or http://forecast.io; or you can use Ruby to generate a random number between 0 and 100.
1. Create two more web pages:
  1. Identify a resource type in your app (products, rides, photos, etc.)
  1. The url "http://localhost:3000/index" should display a list of your items
  1. The url "http://localhost:3000/show" should display just one item from the list
  1. There should be links that take me from one back to the other and back again.


