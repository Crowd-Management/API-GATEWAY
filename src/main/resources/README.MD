#This is the API-GATEWAY
<p>
It has been routed to the customer, matching and shopkeeper as well as market place management system backend.
The procedure is to first run the concerned spring boot applications, and then the api gateway.
Also, the console log just shows a warning that eureka discovery not found. It's just because I have not made the eureka naming server and it is not a major issue.
To use it :
Eg- To run register service on shopkeeper-backend application
The postman request would be http://localhost:8765/shopkeeper/register
as 8765 is the server port of the api gateway.
</p> 