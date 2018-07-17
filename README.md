# OrderMadeSimple

## Description
OrderMadeSimple is a web-app that provides a system of sale interactions for restaurants. Users can manage input orders and foods. Customers can view restaurant inforamtion, make orders, and check reservation. After an order is created, it will be place into an automatic queue. Chef can access the queue and modify the status of those orders. Since the app is web based, users can access via any web-browser supported devices such as computer, tablet, and mobile.

## Implementation and technology
* This app is heavily based on RESTFUL service. 
* Features such as updating reports of ordered foods, the available foods, and active orders will be always synchronized with the database.
* JSON Web Token (JWT) stores the session token for http requests when executing the RESTFUL services, which is mainly used for authentication and authorization.
* CSS framework is availble for computer, tablet, and mobile. 
* QR code generator and a domain will be needed/implemented to accommodate the need of mobile supporting.

