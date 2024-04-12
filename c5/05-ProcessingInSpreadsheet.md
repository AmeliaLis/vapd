# PROCESSING IN SPREADSHEET



## Spreadsheet Table

An Excel table is a specially formatted range of data in a spreadsheet that offers several advantages over a regular data range. It's essentially a way to organize your data in a way that Excel recognizes and can work with more efficiently. Overall, Excel tables are a powerful tool for anyone who works with data in spreadsheets. They can help you save time, improve accuracy, and make your data analysis more efficient.

<https://support.microsoft.com/en-us/office/overview-of-excel-tables-7ab0bb7d-3a9e-4b56-a3c9-6c94334e492c>

1. Open the medical-data.xslx workbook. Familiarize yourself with the use of tables:
    * how to create a table - done
    * how to change a table name - done
    * how to format data - done
    * how to add a total row (count, min, max, average, ...) - done
    * how to add a new column - done
    * how to add new data rows - done
    * how to sort data - done
    * how to display selected data rows - done

1. Using tables, execute the commands below:
    * display a list of women's data - done
    * display a list of people from Poland and Germanty - done
    * calculate the number of women in Slovakia - done
    * display a list of people aged 18-25 - done
    * display a list of people whose height is between 160-180 cm and whose weight is between 55-90 kg - done
    * calculate the number of people who weigh at least 75 kg - done
    * display a list of people whose BMI is normal - done
    * calculate the number of people from Slovakia whose BMI is too high - done
    * calculate the lowest BMI in a group of people from Hungary - done
    * display a list of people from Germany, ordered by height, starting with the tallest person - done



## Pivot Table

A pivot table is an interactive tool used to summarize and analyze large sets of data in spreadsheets like Microsoft Excel. It allows you to reorganize, group, and calculate values from your data to get insights and answer questions quickly. Pivot tables are a powerful tool for anyone who works with data in spreadsheets. They help you gain valuable insights from your data quickly and easily, without needing to write complex formulas.

<https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576>

<https://youtu.be/Vj8SNnat2FA?feature=shared>

1. Open the medical-data.xslx workbook. Familiarize yourself with the use of pivot tables:
    * how to create a pivot table - done   
    * how to change a pivot table name - done
    * how to format data - done
    * how to create in a pivot table rows, columns, and values - done
    * how to create a pivot chart - done


1. Using pivot tables, execute the commands below (create each pivot table in a separate spreadsheet):
    * calculate the number of women and the number of men - done
    * calculate the number of people from each country - done
    * calculate the highest height of people in each country - done
    * calculate the average BMI in each country - done
    * calculate the number of people with a normal BMI in each country - done
    * calculate the average weight of women and the average weight of men in Poland and Slovakia - done
    * using pivot charts, create a chart for each of the above calculations; place the chart below the pivot table



## Power Query

Microsoft Power Query is a data connectivity and data preparation tool. It lets you access data from a wide range of sources and reshape it for your analysis needs. Microsoft Power Query streamlines the process of getting your data ready for analysis in Excel, Power BI, and other Microsoft products. It saves you time and effort by automating data retrieval and transformation tasks.

<https://learn.microsoft.com/en-us/power-query/power-query-what-is-power-query>

1. Familiarize yourself with the use of power query:
    * how to import csv file - done
    * how to import data from a web page - done
    * how to manipulate imported data - done
    * how to connect imported data with a spreadsheet - done

1. Using the medical-data.csv file, execute the commands below:
    * import data from a csv file; in the power query editor, remove the first two columns (first and last names)
    * import data from a csv file; in the power query editor, add a BMI column (calculate the BMI according to the person's height and wage)
    * create a pie chart showing the number of people in each of the countries 
    * create a histogram showing people's ages 
    * create a histogram showing BMI values (too small, normal, too high)


## Tasks

1. The employees.csv file contains data about employees. Using Power Query, import the data into a spreadsheet. Then:
    * display the sorted the data by salary, starting with the highest
    * display employees from Poland, aged at least 50 years
    * calculate the number of women younger than 50

1. Complete the above task but using Jupyter Notebook.

1. The list of Polish cities is available in the cities-in-poland.csv file. Using Power Query, import the data. Then, create the following charts:
    * the total number of inhabitants in each province
    * the area of the largest city in each province

1. Complete the above task but using Jupyter Notebook.

1. The files krk-airlines.csv, krk-flights.csv and krk-passengers.csv contain data about flights from Krakow Airport. Using Power Query, import and merge the data. Then, create the following charts:
    * the number of people traveling to London and Paris 
    * the number of men and the number of women traveling on each airline

1. Complete the above task but using Jupyter Notebook.
