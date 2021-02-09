# NJC-MuleSoft-DAP-Gokul

This is a simple Mock Project for MuleSoft Developer (Internship) at NJC Labs.

A MuleSoft API is build to fetch and push data in Database.

This API is deployed to cloudhub and client-id enforcement policy is applied.

The API url- http://njc-mulesoft-dap-gokul.us-e2.cloudhub.io

client_id=27f8c2e1c7c94a5bbfb3a316b0231c57
client_secret=C771ceF281834F71B8af23C8BEca770a

This API has two methods:
1. Get method - http://njc-mulesoft-dap-gokul.us-e2.cloudhub.io/dbfetch
2. Post method - http://njc-mulesoft-dap-gokul.us-e2.cloudhub.io/dbput

To call this API, please pass the given client id and secret, for Post method - please pass the data as body that 
needs to be pushed into DB in json format.