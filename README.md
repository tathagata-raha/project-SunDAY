# Project : "Sun"Day

## Aim

 An extension of Bing maps that aims to enable the user to travel safely overcoming adverse weather conditions and navigate to the safest location nearby. During disasters it prioritises safety over speed during navigation.

## Motivation

The motivation behind the project comes from the idea that during natural disasters, people usually panic to reach relief centres and are unable to find the shortest or safest path. It also prepares a support system for the users in case of crisis so that the user can call out for help. Besides, what can be better than a notification warning us to take coat or umbrella with us when we are setting off on a journey? Gone are the days when we'd be stranded for hours in the rain or snow!

## Implementation

The extension checks current location of the user and checks meterological data of that location to predict the level of safety.
Safety is measured in 3 levels:

### Pleasant weather:
The app accepts the destination of the user and checks for the routes to his destination from his current location. It analyses the level of weather safety in each of these routes, starting from the shortest one and returns two routes:
1. Safest route
2. Shortest route

### Medium risk:
In addition to returning the safest and shortest routes to the user's destination as in the pleasant conditions, it mentions the precautions needed in course of his journey. For example, if, according to weather reports, there is chance of heavy rain, it alerts the user to carry an umbrella during his journey.

### High risk:
In  case of impending disaster in current location as predicted by meteorological data, the app sends an alert to the user to evacuate the current location and shows the shortest and safest route to the nearest relief centre. It also informs the user's favourite contacts about the impending danger.

In case of high risk in destination while the weather in current location is pleasant or moderate, it also warns the user to cancel his journey.

## Key Features
### Know which route will take you to your destination safely
It accepts the destination of the user and shows the routes according to the implementations provided above
### Know how safe you are or whether you should start your journey:
It gives alert notification in 2 cases:
1. When the current location of the user has a high risk factor
2. When the destination of the user has a high risk factor
### Know where to go when disaster strikes
It lets you know of the nearest relief centres when some natural disaster affects the current location.
### Never ever forget to take your umbrella again:
The app notifies the user about the precautions to take in case of moderate risk factor.
### Get help from friends in case of danger
It sends alert messages to the user's favourite friends and contacts on social media in case of impemding disaster and asks for help.
