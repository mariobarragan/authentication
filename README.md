stormpath authentication

1. go to stormpath.com and make an account.
2. log in and create an api key. then download it and put it somewhere safe.
3. git clone this repository
4. go to the directory and type in $npm install
5. type this and replace the xxx with the api key id you got   (no spaces between the = and x)
  $export STORMPATH_CLIENT_APIKEY_ID=xxx   
6. replace the xxx with your api-key secret   $export STORMPATH_CLIENT_APIKEY_SECRET=xxx
7. go to the application tab on your stormpath account. click my application then use that href in place of the xxx
  $export STORMPATH_APPLICATION_HREF=xxx
8. thats it just type this! $node server.js
