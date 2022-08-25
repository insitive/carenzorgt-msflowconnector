# carenzorgt-msflowconnector
Flow Connector voor CarenZorgt

Import Carenzorgt.swagger.json to PowerAutomate - And use 'Get Tokens' to retrieve the Carenzorgt Bearer token.

With the token you can now download data based on the API.
Option 1
https://www.carenzorgt.nl?landing_user_session_form[email]={{Username}}&landing_user_session_form[password]={{PASSWORD}}&landing_user_session_form[remember_me]=1
Option 2
https://www.carenzorgt.nl/api/v1/tokens
x-www-form-urlencoded 
grant_type=password  // doesn't seem to do much
email={{Username}}
password={{PASSWORD}}

