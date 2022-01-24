# About the repository        

![npm](https://img.shields.io/badge/npm-8.1.2-green)

The Food Order App is created by using React Native framework. The app has 3 pages in total: Home, Restaurant and Order Delivery. The UI designer of the app is Ilia Utkin.


## Installation and running the server

The [Node.js](https://nodejs.org/) v16.13.1 and Expo v44.0.0 were used. For installation, install the dependencies and start the server.

```sh
git clone https://github.com/ozgur-okt/React-Native-Food-Order-App-with-Google-Maps
cd React-Native-Food-Order-App-with-Google-Maps
expo init
```
#### Start the server
```sh
expo start
```
Now your browser is going to open.

## Screen 1 - Home.js
This component includes all the categories and foods. Each food has the restaurant name, distance, rating , category information and expensiveness level. 

![app1](https://user-images.githubusercontent.com/73358116/150804211-24dfda44-f5c3-4a57-9325-255dac56daac.jpg)


## Screen 2 - Restaurant.js
When you choose a food to order, here you see the name of restaurant as header,the picture of the food, price and details. "Order" button nagivates the page of map.

![app2](https://user-images.githubusercontent.com/73358116/150804237-dd67062a-31e3-40fe-925c-8986ac0a6697.jpg)


## Screen 3 - OrderDelivery.js - Google Maps Direction
This page shows where the courier is and restaurant is. The distance and direction are defined as an orange-line. Courier guy has rating info besides "Call" and "Message" options.


![app3](https://user-images.githubusercontent.com/73358116/150804253-0409fa4b-dcdb-41ce-a869-8f49b2295686.jpg)



## The future improvements
There are certain issues that need to be fixed.The first issue is that, on the map page, the app is not recognizing the direction line though all my effords. It shows only the 
location of the restaurant and courier.
The second issue is that second page which is restaurant page is not recognizing the top-line the phone screen and gets into the status bar. A new resizing is needed. 

## License

This repo is released under the MIT License.

