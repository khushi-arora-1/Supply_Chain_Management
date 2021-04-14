# Supply_Chain_Management
Data Analysis project that involved building a model which predicts whether the finished goods, i.e medicines from pharmaceutical companies would be delivered to various international locations on time or not. The model is trained and tested using Decision tree algorithm. According to the problem statement, the pharmaceutical companies are majorly dependent on their supply chain management for the timeliness delivery of their supplies. The on time delivery of these products in the right condition is very essential. The delivery of these products to the small countries of Africa is equally important as they depend on the external pharmaceutical companies. Hence arises a need to have a robust Supply chain Management with technological upgradation through Machine Learning tools.

#### Factors taken into consideration (as taken from the dataset):

1. Demand Forecast:
- The customer demand patterns are analyzed by many companies and based on this pattern the pharmaceuticals start the manufacturing of a particular drug.
2. Number of products produced:
- There should be some inventory kept so that the company is prepared for the unexpected demand from the customer. Hence, the production of the drugs is done based on the demand and inventory accordingly.
- The drugs are manufactured and grouped as a pack of 10-15 tablets. These packs are being shipped in bulk to different places.
3. Transportation means:
- The drugs manufactured in the US are to be shipped to other countries. So, the drugs are mostly shipped through air as it reaches the destination early when compared to other means of transport.
- The other means of transport are ships and trucks.
4. Transportation Cost:
- All the pharmaceuticals use airways for the shipment of its products. Hence, the cost of the cargo is based on the weight being shipped.
5. Damage to the product while shipping it/transportation losses:
- During transportation of the products from the factory to different countries, there is a possibility of damage that could be caused to the goods due to various factors such as accidents, improper packaging etc.
6. Delay factors like weather:
- The products might not reach the stores on time due to delay in the delivery time because of factors like storm ,turbulence ,rain etc for air shipment.

##### Libraries that were Imported
- PANDAS: In computer programming, pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license. The name is derived from the term "panel data", an econometrics term for data sets that include observations over multiple time periods for the same individuals. Its name is a play on the phrase "Python data analysis" itself.
- MATPLOTLIB: Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK+. There is also a procedural "pylab" interface based on a state machine (like OpenGL), designed to closely resemble that of MATLAB, though its use is discouraged. SciPy makes use of Matplotlib.
- NUMPY: NumPy is one of the most powerful Python libraries. It is used in the industry for array computing. This article will outline the core features of the NumPy library. It will also provide an overview of the common mathematical functions in an easy-to-follow manner.
- SEABORN: Seaborn is a library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures.Seaborn helps you explore and understand your data. Its plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots. Its dataset-oriented, declarative API lets you focus on what the different elements of your plots mean, rather than on the details of how to draw them.
- PLOTLY: The Plotly Python library is an interactive, open-source plotting library that supports over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases.Built on top of the Plotly JavaScript library (plotly.js), plotly enables Python users to create beautiful interactive web-based visualizations that can be displayed in Jupyter notebooks, saved to standalone HTML files, or served as part of pure Python-built web applications using Dash. The plotly Python library is sometimes referred to as "plotly.py" to differentiate it from the JavaScript library.
