# How can I use DNS to verify my domain with Google Search Console (Webmaster Tools)?

When setting up Google Search Console you will be asked to verify your domain. A recommended method which will work as long as you are using our StackDNS nameservers is to add the Google verification code as a TXT record for your domain.

To do this, go to the “Manage DNS” section of your control panel. Towards the bottom of the Manage DNS page you will see 3 inputs to allow you to add new records:

* Leave the “Name” field blank
* Select “TXT” for Type
* You should now enter record given by Google in the “Data” input.

Save your changes and head back to Google to run the verification. DNS updates across our nameservers are usually done instantly, but in rare cases can take up to 2 minutes.
