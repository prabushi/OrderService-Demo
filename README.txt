Create

Input: curl -X POST -d @request.json http://localhost:8290/abcafe/placeorder -H "Content-Type: application/json" -v

Output: {"Message" : "Successfully placed the order.", "Order details": {"ID" : "1234", "Customer Name":"Bob", "Price" : "USD 150"}}

==========

Cancel

Input: curl -X POST -d @requestcancel.json http://localhost:8290/abcafe/cancelorder -H "Content-Type: application/json"

Output: {"Message" : "Successfully cancelled the order.", "Order Id": "5678"}

==========

Update

Input: curl -X POST -d @requestupdate.json http://localhost:8290/abcafe/updateorder -H "Content-Type: application/json"

Output: {"Message" : "Successfully updated the order.", "Order details": {"ID" : "1234", "Customer Name":"Alice", "Price" : "USD 175"}}

==========

