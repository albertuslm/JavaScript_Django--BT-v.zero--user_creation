# Using the Braintree SDK v.zero with Javascript & Python (Django)

This is an example of the Braintree v.zero SDK for creating users in web applications, that will be stored in Braintree and related to merchant Braintree account. In the client side it uses `javascript` and for the server side `python` (runing Django framework) is used.

## Technology

This demo uses

* Python 2.7
* [Django 1.7.1](https://www.djangoproject.com/)

## Running the server

* Before run server, install braintree package using one terminal:

	* `pip install braintree`

## Running the website app

* Run the server from your terminal:
	* In the `root` folder of the project:
		`python manage.py runserver`
	* Select either of these payment methods:
		* (PayPal)
			* Fill in the following credentials:
				* Email: `us-customer@commercefactory.org`
				* Password: `test1234`
			* Click `Agree` to accept future payments
		* (Credit Card) Fill in the following credentials:
			* Number: `4111 1111 1111 1111`
			* Expiration date: `11/15`
  			* CVV: `123`
	* Click on `Create User & add this payment method`
	* You will see a message that says __"Customer ID: [customer_id]"__


## Useful links

* [Full documentation for the Braintree Client SDK for javascript+python](https://developers.braintreepayments.com/javascript+python/start/overview)
