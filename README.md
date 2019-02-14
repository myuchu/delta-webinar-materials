# delta-webinar-materials

There are 3 objects in this repo:

1) Delta_Inv_Setup notebook: This notebook is triggered by the Delta - Inventory notebook. Please look at the notebook setup first before running anything. There is code that should be run ONLY ONCE.

2) Delta - Inventory notebook: The main notebook demoed during the webinar.

3) `current_inventory.parquet` dataset: place this parquet file in a specific directory



current_inventory.parquet
==========================================

This data set was obtained from http://archive.ics.uci.edu/ml/datasets/Online+Retail.  The source of the data is:
Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

This dataset was modified by the addition of 80,000 generated additional rows with some columns removed to simulate an inventory dataset.


### Data Set Information


This was originally a transnational data set that contained all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. It was modified to simulate an inventory stock.


Attribute Information:

StockCode: Product (item) code. Nominal, a string of characters uniquely assigned to each distinct product. 
Description: Product (item) name. Nominal. 
Quantity: The quantities of each product (item) per transaction. Numeric.	
UnitPrice: Unit price. Numeric, Product price per unit in sterling. 
Country: Country name. Nominal, the name of the country where each customer resides.
	

### License and/or Citation

Applicable citations:

Daqing Chen, Sai Liang Sain, and Kun Guo, Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197–208, 2012 (Published online before print: 27 August 2012. doi: 10.1057/dbm.2012.17).
