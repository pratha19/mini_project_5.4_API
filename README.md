# mini_project_5.4_API

For this mini project, we will focus on equities data from the Frankfurt Stock Exhange (FSE), which is available for free. 
We'll try and analyze the stock prices of a company called Carl Zeiss Meditec, which manufactures tools for eye examinations, 
as well as medical lasers for laser eye surgery: https://www.zeiss.com/meditec/int/home.html. 
The company is listed under the stock ticker AFX_X.

You can find the detailed Quandl API instructions here: https://docs.quandl.com/docs/time-series

While there is a dedicated Python package for connecting to the Quandl API, we would prefer that you use the requests package, 
which can be easily downloaded using pip or conda. You can find the documentation for the package 
here: http://docs.python-requests.org/en/master/

Finally, apart from the requests package, you are encouraged to not use any third party Python packages, 
such as pandas, and instead focus on what's available in the Python Standard Library 
(the collections module might come in handy: https://pymotw.com/3/collections/ ). 
Also, since you won't have access to DataFrames, you are encouraged to us Python's native data structures - 
preferably dictionaries, though some questions can also be answered using lists. You can read more on these data structures 
here: https://docs.python.org/3/tutorial/datastructures.html

Keep in mind that the JSON responses you will be getting from the API map almost one-to-one to Python's dictionaries. 
Unfortunately, they can be very nested, so make sure you read up on indexing dictionaries in the documentation provided above.