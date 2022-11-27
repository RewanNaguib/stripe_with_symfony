# stripe_with_symfony
Integration of stripe with Symfony framework

# steps 
1) You have to create an account on stripe.com
2) Put your SECRET_API_KEY in .env and use it the "PaymentController"
3) "https://127.0.0.1:8001/payment" This is the main page that contains Checkout button
4) "https://127.0.0.1:8001/checkout" This is the URL of the checkout button it will redirect to stripe page that takes the payment (visa card) info from the user 
5) If the card information is correct then the page will be redirect to "https://127.0.0.1:8001/success_url"
6) If the card information is incorrect then the page will be redirect to "https://127.0.0.1:8001/cancel_url"
