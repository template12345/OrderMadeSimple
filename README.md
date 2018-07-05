Objectives:
OrderMadeSimple is a web-app mainly focuses on providing a sales and intraction system for restaurant.

Managers are able to manage food/ input order.
Customers can input order, check reservation, and restaurant information.
The input orders will put into a automatic queue in the kitchen. 
Chef in the kitchen can access the orders in the queue and modify the status of the orders.
Users can access the system via any web-browser supported device. including portable devices such as tablets and mobiles.

Implementation and technology:
This is a web-app that's heavily based on RESTFUL service. 
Features such as actively updating reports of ordered foods, the available foods, and active orders relie on RESTFUL API 
as they need to be and will be always synchronized with the database.
JSON Web Token (JWT) stores the session token for http requests when executing the RESTFUL services, which is mainly used for authentication and authorization.
CSS framework is not limited to desktops only but also covers mobile css in order to fit both
Androids and IOS. 
In order to support mobile ordering, QR code generator and a domain will be needed/implemented to accommodate the need of mobile supporting.

