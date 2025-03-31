# EPM SaaS Bruno Collection

## Instructions for usage

Instructions for Bruno client REST testing framework

1.  Create a new environment; Click anywhere in the collection -> Collection Environments in the top-right of the window.

2.  Select Configure.

3.  Add variables for the following:
  1. EPM_SERVER
  2. EPM_LOGIN
  3. VERSION
  4. SET_ID
  5. USERNAME
  6. PASSWORD
  7. TOKEN
  8. APP_GROUP_ID

## Notes 

1. You will not have a token at first.  You will get the token in the response data from the initial ``POST Authenticate/`` request.  Copy that into the value of the environment variable that you created.
2. ``USERNAME`` and ``PASSWORD`` can be passed in as they would normally be entered signing in through the native login (``user@domain/password``).
3. Run 'Get sets' first to get a list of the user-defined sets that you are assigned to.
4. ``EPM_SERVER`` is the your CyberArk EPM tenant id, whereas ``EPM_LOGIN`` is the login URL for your tenant.
5. Be sure to replace ``<subdomain>`` placeholder in the environment variable.