# Report-Accessiblility

# Overview :

• Enhance the accessibility of the visuals using descriptive titles, markers, alt text, and accessible coloring.

• Improve the accessibility of the overall report by changing the tab order and using themes.

• Discuss the improvements made to the report, outlining their benefit for users with disabilities.

# Case Study : 

  Adventure Works recently welcomed new members to its sales team, including Logan, who is visually impaired. Committed to inclusivity, the directors have asked the data analytics team to 
  ensure all reports are accessible, aiming to make them 
  more user-friendly for a wider audience. You are assigned the task of incorporating accessibility features to enhance and refine an existing report that contains sales data for the months 
  of February, March, and April across various sales 
  regions, aligning with the best practices you have learned.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Step 1: Open the report in Power BI Desktop.

      • Download and open the "Creating an Accessible Report" file in Power BI Desktop.

  This step gives you access to the current structure and contents of the report, enabling you to determine where necessary improvements to accessibility need to be made.

![image_alt](https://github.com/DSgenes/Report-Accessiblility/blob/47d002ac492d4a1839c03bd7645917356f811c3c/Screenshot%201.png)

# Step 2: Add a meaningful report title

  Provide a clear, concise title to give context and help all users, including those with disabilities, understand the report’s focus.

      • To add the title, select the report title and update it to "Adventure Works Quarterly Regional Sales Report."

  ![image_alt](https://github.com/DSgenes/Report-Accessiblility/blob/6b49d96d2e28c094b575cec09f098db4bec90a5a/Screenshot%202.png)

# Step 3: Improve the accessibility of chart visuals

      • Ensure the visuals have clear and descriptive chart titles, as shown in the screenshot below.

![image_alt](https://github.com/DSgenes/Report-Accessiblility/blob/649727e42ccff4d60233b94371930243137995b4/Screenshot%203.png)

# Improve Chart Titles : 

      • Select the clustered column chart (bottom left), open the Format tab, expand Title, and change it to: "Monthly Order Quantities by Order Status."

      • Repeat for the line chart (top right), updating the title to: "Monthly Order Total by Product Region."
      
      • Repeat for the stacked bar chart (bottom right), changing the title to: "Monthly Order Quantities by Product Region."

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Display Markers in the Line Chart:

      • Select the line chart (top right), then click the Focus mode button to zoom in.
       
      • Open the Format tab, scroll to Markers, and toggle it to On.
       
      • To enhance accessibility, expand Markers settings, select a region, and change the marker shape. Repeat this for the other regions with different marker shapes.

![image_alt](https://github.com/DSgenes/Report-Accessiblility/blob/2ed92956753dd82988b76030c061e7865aacd4e1/Screenshot%205.png)

      • Exit Focus Mode by clicking Back to report 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Add Alt Text:

# Clustered Column Visual (bottom left):

     • Select the visual, go to the Format tab, expand Alt text, and set the alt text to:
    
     • "From February to April, canceled orders were the lowest, processing showed steady growth, and shipped surged in April."

![image_alt](https://github.com/DSgenes/Report-Accessiblility/blob/6989ffa055d2d53efcedce7e3b4badbf27233f56/Screenshot%206.png)

# Line Chart Visual (top right):

     • Select the visual, open the Format tab, expand Alt text, and set the alt text to:
    
     • "Order totals increased monthly across regions, with Europe leading. North America and Europe grew monthly, especially in April. Asia’s growth slowed from March to April, with totals 
     
        similar to North America, except in March when Asia overtook."

![image_alt](https://github.com/DSgenes/Report-Accessiblility/blob/023ac9a693a65f985c3ffd2d543e966e8cccf205/Screenshot%207.png)

# Stacked Bar Visual (bottom right):

    • Select the visual, open the Format tab, expand Alt text, and set the alt text to:

    • "Order quantities increased monthly in all regions, with Europe leading and accelerating growth. Asia’s growth peaked from February to March, while North America showed the opposite 
     
       trend."

![image_alt](https://github.com/DSgenes/Report-Accessiblility/blob/07853034069c8599b88e84983fb251f63238d688/Screenshot%208.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Use an Accessible Theme:

   • Open the Themes dropdown in the View ribbon.
  
   • Select a theme from the Accessible themes category, such as Accessible City Park.

![image_alt](https://github.com/DSgenes/Report-Accessiblility/blob/d12c956804d53efa03f87b07c03c2701d3c3414a/Screenshot%209.png)

   • The selected theme will instantly apply to all visuals in your report, as shown in the screenshot below.

![image_alt](https://github.com/DSgenes/Report-Accessiblility/blob/c49a2d5077271d6d8a0320ae09baa9d998ffe8bb/Screenshot%2010.png)

# Note:
     You can customize each chart item's color by selecting visuals individually. In the Format tab, expand the relevant section (e.g., Lines for the line chart, Columns for the clustered 
     column chart, or Bars for the stacked bar chart) to adjust the colors from light to dark shades.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Step 4: Enhance Chart Navigation by Changing Tab Order

![image_alt]()

    1. In the View tab, under Show panes, select Selection to open the Selection pane.
      
    2. Drag and reorder the visuals in the following order (as shown in the screenshot below):
      
    • Text box
      
    • Monthly Order Total by Product Region
      
    • Monthly Order Quantities by Order Status
      
    • Monthly Order Quantities by Product Region

![image_alt]()
