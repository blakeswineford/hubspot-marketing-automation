# hubspot-marketing-automation

This script reads a list of website URLs from a CSV file, sends HTTP requests to each website, and checks if they are using HubSpot for marketing automation. If a website is using HubSpot, it prints a message saying so, otherwise it prints a message saying that it is not. The script requires the `csv` and `requests` libraries to be installed in Python. The CSV file should have one URL per line.

Here is an example of the output:

```
http://www.example.com/ no
http://www.exampletwo.com is using HubSpot for marketing automation.
http://www.examplethree.com no
```
