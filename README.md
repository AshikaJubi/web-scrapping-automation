# Exercise 5: Web Scraping Data

### Reg No: 212221040013

## AIM:
  To scrape data from a website and save it to a CSV file manually.

## Activities Required:
  1. Use Browser
  2. Get Text
  3. Build Data Table
  4. Add Data Row
  5. Write CSV

## Procedure:
  1. Choose a website with structured data (e.g., a product list or any repeating data).
  
  2. Open **UiPath Studio** and create a new project called **WebScrapingManualAutomation**.
  
  3. In the **Activities Panel**, search for **Open Browser** and drag it into the **Designer Panel**.
  
  4. Set the **URL** property of **Use Browser** to the website’s URL (e.g., `"https://example.com/data"`).
  
  5. In the **Activities Panel**, search for **Build Data Table** and drag it below the **Open Browser** activity.
  
  6. Add columns in the **Build Data Table** activity for the data you want to scrape (e.g., Product Name, Price, etc.).
  
  7. Use **Get Text** activity to extract the required data fields from the web page.
  
  8. After extracting data, use the **Add Data Row** activity to add the data to the data table (use a variable to store extracted text and insert it into the row).
  
  9. Repeat the **Get Text** and **Add Data Row** activities for each field you need to scrape.

  10. Once data scraping is done, use **Write CSV** activity to save the scraped data into a CSV file.
  
  11. Set the **FileName** property of **Write CSV** to the desired path (e.g., `"C:\Users\YourName\Documents\scrapedData.csv"`).

  12. Save and Run the workflow.

## Example Workflow:
  ![image](https://github.com/user-attachments/assets/9340a2a6-fd6f-4d40-aa6a-afdcaddf2e28)

## Output:
  ![image](https://github.com/user-attachments/assets/5f045ebb-c7be-4f25-8e7e-d4c28ee9cb7e)

## Result:
  Thus, the data is manually scraped from the website and saved to a CSV file.
