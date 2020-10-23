# sentimentAnalysisWithZenuity
this is simple idea to scrap data from a page and send it to kafka broker.
<a href="https://ibb.co/mth61tf"><img src="https://i.ibb.co/MpPMWpF/Screenshot-2020-10-23-18-22-49.png" alt="Screenshot-2020-10-23-18-22-49" border="0"></a>

we have webscrapper.py that scrab data from zenuity page in glassdoor
i've used beautiful BeautifulSoup  library for scraping the data
after it transfer data into kafka topics ( positive - negative - highlights ) 
and this step we have 3 data consumer app ( highlights.py - negative-consumer.py - positive-consumer.py)
after consuming the data from related topics 
