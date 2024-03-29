# Decentralized merchendise management
![alt text](https://raw.githubusercontent.com/abhineetraj1/merchendise-management/main/screenshot.png)
This project is a communication app for businesses that sell merchandise. It allows retailers to send orders to wholesalers and track their order history. Wholesalers can store orders from retailers, order products from manufacturers, and track pending and delivered orders. Manufacturers can receive orders from retailers, store them in their system, and track pending and delivered orders.

## Installation

*	Install python3 and external libraries required

```
pip3 install -r requirements.txt
```

*	You need to buy ngrok premium version so that you can expose your localhost to custom ngrok subdomain, so that if the application closes, it can reconnect at same subdomain.
*	Setup the `localhost:port` in wholesaler, retailer and manufacturer app according to the ngrok subdomain set in the each system.
## Note

Make sure the cache file generated by each file should not be deleted, because these files contain important info for user.

## Features
*	Store order history
*	Store pending orders
*	Decentralised data transfer system
*	Efficient tracking system

## Languages and tools used
<p align="left"> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

## Developer
*	[Abhineet Raj](https://github.com/abhineetraj1)
