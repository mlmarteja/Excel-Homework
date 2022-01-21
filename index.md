## How to Create PivotTables in Excel

In this tutorial, I will illustrate how to utilize a PivotTable tool in Excel. PivotTables is a generic terms that is coined by Microsoft. According to Microsoft, [PivotTable](https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576) is a powerful tool that is used to calculate, summarize and analyze data. 

In addtion, it allows the user to see data comparisons, patterns, and trends. This allowsthe user to extract the significat information from a large detailed data set. For example, in this tutorial we will utilize Plant Height Data. Lets say that we want to only comparethe heights of each plant, could use PivotTables to illustrate sum of the heights of each of the plants that are presented in the data. 

In this example webpage will provide basic instructions on how to utilize this tool and other operations that can be done.


## Step 1 - Open Microsoft Excel
Download [Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel). You could either buy it or try it for free. When Excel is downloaded, make sure **Sign In** or **Sign Up** with your Microsoft Account. 


## Step 2 - Create a SpreadSheet or Add an Existing Data Set
Once the Excel has been launched, start a new spreadsheet. To start a new spread sheet, select **Blank workbook** and start adding data.
![StartANewSheet](https://user-images.githubusercontent.com/93753370/150057790-bdb1c6bc-3629-46d9-bdfd-dac51ded606b.png)

An alternative is to just open an existing data set by selecting **File**. For this tutorial, I used [Plant Height Data](https://github.com/mlmarteja/Excel-Homework/blob/91b422a0b3023786847a292e1e368ff3746410d2/Plant%20Height%20Data%20-%20Data.csv) that was provided by Arielle from the previous Data Science Class

Click on the Image below to know how to open an existing file on Excel
[![Alternate Text](https://user-images.githubusercontent.com/93753370/150379227-129ba319-5562-4386-9306-2e9553361b71.png)](https://user-images.githubusercontent.com/93753370/150376768-3db48c42-bcfb-4914-a01d-cefd17acf407.mp4 "Open New Chat")
In the video, it shows that you have to option to open an existing sheet that has been previously viewed or **Browse** to find a the spreadsheet.

## Step 3 - Insert -> PivotTable
To navigate to the PivotTable, on the top menu bar, click on **Insert**. Under that menu, the option to create a **PivotTable** should be available. Once the PivotTable is found, click on it.

![StartANewSheet](https://user-images.githubusercontent.com/93753370/150380610-664d91b8-7d76-4ef9-b8ef-ddc087de5fac.png)

Once PivotTable is selected, a window will pop up and display a menu that will ask the user for the range of data that will be used in the PivotTable. For the Plant Height Data, the **Table/Range** that will be used for this example will be the whole sheet which is from columns A to AH and rows 1 to 179. To choose where you want the PivotTable to be placed, you could either select **New Worksheet** or **Existing Worksheet**. In this case, we will work in a new worksheet. Whatever you will need to commit the range that will be used, select **ok**.
![PivotTableRange](https://user-images.githubusercontent.com/93753370/150380713-7f9bbe6b-3be3-43e5-bf3e-8f61d9704429.png)


## Step 3 - Building Your PivotTable.
Once you have selected **ok**, a new sheet should be created and a task pane called **PivotTable Fields** should appear.

The PivotTable Fields contains the fields of data, the areas, defer layout update, and the update button. As seen in the picture below, the area contains four different areas.
- Filters
- Columns
- Rows
- ∑ Values

![InsetToPivotTable](https://user-images.githubusercontent.com/93753370/150591109-c413bba3-6cb1-4f9f-ad85-c97dc35ae9f1.png)


Note: When you click on the chosen fields, they will be put into default areas. In other words, non-numeric fields are added **Rows**, data and time is put into **Columns**, and numeric fields are placed under **Values**.

For example, I had the following fields selected: Genus_species, Family, height, loght, and County. These fields were automatically put into the areas bellow. The Rows contained non-numeric fields Family, height, and Genus_species. The Values contained numeric fields height, and loght.
![PivotTableExample](https://user-images.githubusercontent.com/93753370/150448671-f436eedc-3407-4988-86ee-46a51a45502a.png)
