# Investment-Support-System
Decision support system to aid e-commerce investors

1. This project is a stock DSS which aims to combine clarity of presentation and fluidity of navigation, with comprehensiveness of analyses and efficiency of provision of vital information to a potential investor, whilst particularly aiming to maintain ease of use and understandability.
The welcome page provides the potential investor with a straightforward introduction and an easy to use, yet effective interface which can be used to seamlessly navigate throughout the system. 
A simple menu displays two options which are selectable via clickable buttons. One button brings the user directly to the single stock analysis section of the DSS, whilst the other brings the user directly to the three stocks analysis section of the DSS. Similar buttons are located on the other two visible sheets. They aim to provide efficient, effortless navigation around the system.
Thanks to a macro, regardless of which sheet the Excel document was last saved on, the welcome page will always be initially presented on screen upon opening the workbook.
Actions performed by all recorded macros in the system are highly fluid and seamless, thanks to the addition of a specific line of code which eliminates bothersome screen updating and flickering.

2.   Single stock:
 	This section of the DSS focuses on offering the potential investor a comprehensive analysis of the performance of each individual stock, whilst still ultimately aiming to prioritise usability, understandability, and clarity. 

3.   Three stocks:
 	This is the comparative section of the DSS. It primarily focuses on clarity of presentation, fluidity of navigation, ease of use, and efficiency of provision of vital information to the potential investor.

What’s very important to mention are the workings of the macros which generate the charts and tables throughout the workbook. The datasheets used to generate these are hidden by default. When the user selects a button to generate a chart or table, the macro assigned to it unhides the relevant datasheet(s), extracts the data, and generates the chart/table. The macro thereafter hides the datasheet(s) before navigating back to the original page and displaying the desired chart/table. Of course, this quite extensive, tedious process is conveniently hidden from the user by the macro aforementioned in the project introduction.
