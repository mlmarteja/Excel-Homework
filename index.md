## How to Create PivotTables in Excel

This tutorial will illustrate how to utilize a PivotTable tool in Excel. PivotTables is a generic terms that is coined by Microsoft. According to Microsoft, [PivotTable](https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576) is a powerful tool that is used to calculate, summarize and analyze data. This statistical tool us utilized to summarize and organize the rows and columns that the user wants to represent in the streadsheet without changing the spreadsheet of the dataset. Essentially, it "pivots" the data to provide a different perspective.

In addtion, it allows the user to see data comparisons, patterns, and trends. This allows the user to extract the significat information from a large detailed data set. For example, in this tutorial we will utilize Plant Height Data. Lets say that we want to only comparethe heights of each plant, could use PivotTables to illustrate sum of the heights of each of the plants that are presented in the data. 

In this example webpage will provide basic instructions on how to utilize this tool and other operations that can be done.


## Step 1 - Open Microsoft Excel
Download [Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel). You could either buy it or try it for free. When Excel is downloaded, make sure **Sign In** or **Sign Up** with your Microsoft Account. 


## Step 2 - Create a SpreadSheet or Add an Existing Data Set
Once the Excel has been launched, start a new spreadsheet. To start a new spread sheet, select **Blank workbook** and start adding data.
![StartANewSheet](https://github.com/mlmarteja/PIvot-Tables/blob/8a61e263ef7a1b55d6d88a965f9b6ec7b5aa5170/StartANewSheet.png)

An alternative is to just open an existing data set by selecting **File**. For this tutorial, I used [Plant Height Data](https://github.com/mlmarteja/Excel-Homework/blob/91b422a0b3023786847a292e1e368ff3746410d2/Plant%20Height%20Data%20-%20Data.csv) that was provided by Arielle from the previous Data Science Class

Click on the Image below to know how to open an existing file on Excel
[![open](https://github.com/mlmarteja/PIvot-Tables/blob/8a61e263ef7a1b55d6d88a965f9b6ec7b5aa5170/Screenshot%202022-01-20%20112215.png)](https://user-images.githubusercontent.com/93753370/150376768-3db48c42-bcfb-4914-a01d-cefd17acf407.mp4 "Open New Chat")
In the video, it shows that you have to option to open an existing sheet that has been previously viewed or **Browse** to find a the spreadsheet.

## Step 3 - Insert -> PivotTable
To navigate to the PivotTable, on the top menu bar, click on **Insert**. Under that menu, the option to create a **PivotTable** should be available. Once the PivotTable is found, click on it.

![InsetToPivotTable](https://github.com/mlmarteja/PIvot-Tables/blob/8a61e263ef7a1b55d6d88a965f9b6ec7b5aa5170/InsetToPivotTable.png)


Once PivotTable is selected, a window will pop up and display a menu that will ask the user for the range of data that will be used in the PivotTable. For the Plant Height Data, the **Table/Range** that will be used for this example will be the whole sheet which is from columns A to AH and rows 1 to 179. To choose where you want the PivotTable to be placed, you could either select **New Worksheet** or **Existing Worksheet**. In this case, we will work in a new worksheet. Whatever you will need to commit the range that will be used, select **ok**.
![PivotTableRange](https://github.com/mlmarteja/PIvot-Tables/blob/8a61e263ef7a1b55d6d88a965f9b6ec7b5aa5170/PivotTableRange.png)


## Step 3 - Building Your PivotTable.
Once you have selected **ok**, a new sheet should be created and a task pane called **PivotTable Fields** should appear.

The PivotTable Fields contains the fields of data, the areas, defer layout update, and the update button. As seen in the picture below, the area contains four different areas.
- Filters
- Columns
- Rows
- ∑ Values

![PivotTable Fields](https://github.com/mlmarteja/PIvot-Tables/blob/8a61e263ef7a1b55d6d88a965f9b6ec7b5aa5170/PivotTable%20Fields.png)

Note: When you click on the chosen fields, they will be put into default areas. In other words, non-numeric fields are added **Rows**, data and time is put into **Columns**, and numeric fields are placed under **Values**.

For example, I had the following fields selected: Genus_species, Family, height, loght, and County. These fields were automatically put into the areas bellow. The Rows contained non-numeric fields Family, height, and Genus_species. The Values contained numeric fields height, and loght.
![PivotTableExample](https://github.com/mlmarteja/PIvot-Tables/blob/8a61e263ef7a1b55d6d88a965f9b6ec7b5aa5170/PivotTableExample.png)

### Working with PivotTable Values
For this part we will be using the [Game] dataset that was found in [Kaggle](https://www.kaggle.com/). The dataset was created and posted by Khalid called [PC Games Sales](https://www.kaggle.com/khaiid/most-selling-pc-games). When working with the Values area, PivotTable firlds will create defult fields such as **SUM**. If you want the change any calculations that you want to present in the **Values** area, you can right click and select **Value Fields Settings** option.
![valuearea](https://github.com/mlmarteja/PIvot-Tables/blob/8a61e263ef7a1b55d6d88a965f9b6ec7b5aa5170/valuearea.png)

WHen the Value Field Settings pane is visible, you change change the type of calculation that is usedto summarize the data from the fields. For this example, instead of selecting **Sum** to display the sum of the sales, we will select **Average** to display the average of the sales.
![ValueSettings](https://github.com/mlmarteja/PIvot-Tables/blob/8a61e263ef7a1b55d6d88a965f9b6ec7b5aa5170/ValueSettings.png)
Here is the new PivotTable with the average sales.
![AverageSales](https://github.com/mlmarteja/PIvot-Tables/blob/8a61e263ef7a1b55d6d88a965f9b6ec7b5aa5170/AverageSales.png)
