# scrapper
web scrapper using scrapy

# Test
Ready for the first test? Simply run the following command within the “stack” directory:

	scrapy crawl stack

Along with the Scrapy stack trace, you should see 50 question titles and URLs outputted. You can render the output to a JSON file with this little command:


	scrapy crawl stack -o items.json -t json

	
We’ve now implemented our Spider based on our data that we are seeking.