# Seneafood

Seneafood is a store management web application.
You can manage employees, products, orders, visits and much more !

Disclaimer: for privacy reasons, the source code of the mobile app and web app cannot be commited.
This project has been realised for one of my customers.

**Context**

This solution is composed of a web application (back office) and a mobile application.
It has been developed by myself for a food company CEO.
He needed a mobile application so that his employees could take pictures of his products in the store shelves.
He alse needed a way to create accounts for his employees, see the pictures, the products, the stores, etc...

**Demo**

![Seneafood animation](demo/animation.gif)

**How the mobile application works**

- Download the seneafood mobile application
- Login into your account and choose the store you're visiting
- Start to take pictures of the seneafood supermarket shelf
- Input the quantities of each product on the shelf
- Click the send button to submit

**How the back office works**

- Go to the seneafood [back office](https://seneafood-ui.herokuapp.com/)
- Login into your account and manage your store online (create products, change the status of orders...)

![Seneafood backoffice animation](demo/backoffice-animation.gif)


**Backend and backoffice**

I used mongoDB as the database and node.js to create the API

![](demo/arch.png?raw=true)
