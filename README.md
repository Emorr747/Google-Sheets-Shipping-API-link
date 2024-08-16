# Google-Sheets-Shipping-API-link
Hello and welcome

Intro:
I made this tool mainly as a way to get a shipping quote and incorporate it with Google Sheets
It's more of a convenience tool than a neccessity tool. I made this more for if you are wanting to use it for a shipping rate via origin and destination zip code for the products you sell this is faster than logging in to UPS, getting the all the dims, entering it on a second page, then on the third page you enter in the location, to finally get the rate you were looking for

You will need to access/create a UPS Developer's account and create an app as the API key will vary from user to user.
In your API App you will need to include:
1. Authorization ( OAuth)
2. Rating
  
After the code is pasted in your App Script you will need to set up a trigger:

1. choose which function to run: getUPSSHippingRates (Or whatever you want to name this)
2. Which runs at deployment: Head
3. Select event source: From spreadsheet
4. Select event type: On edit

Once these have been set up you will be good to go.
I hope this helps
