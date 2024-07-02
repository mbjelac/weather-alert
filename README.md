# Automated DHMZ weather alert

[DHMZ](https://meteo.hr/) - the Croatian meteorological society - doesn't have an automated way of sending weather alerts. I suppose the weather in Croatia has not been so critical so this hasn't been so important.

However, in the last years we have been getting more and more extreme weather events, so I assembled a little automated alert sender.

The DHMZ site has a public URL on which they regularly publish weather alerts in XML format. This alert sender downloads the XML, parses it and filters for weather alerts important to me, assembles them in a rudimentary HTML and sends them to me via e-mail.

This is fully automated using Github Actions. Check out the workflow file to see how it ticks. Feel free to fork or otherwise transfer the code and make your own alert sender.
