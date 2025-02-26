Data Extraction:
- Manually extracted key financial data for the last three fiscal years from the 10-K filings of Microsoft, Tesla, and Apple. 
- Navigated to the SEC's EDGAR database for each company, found the 10-K filings for the last three fiscal years.
- Extract the following financial figures manually : Total Revenue, Net Income, Total Assets, Total Liabilities, and Cash Flow from Operating Activities.
- Organized the Data compiled form extracted data into an Excel spreadsheet for easy reference during my Python analysis.


Analysis:
- imported pandas library to work with the organized data in excel format.
- Converted Excel file to a CSV file for easier handling, then loaded it into a DataFrame.
- Using pandas calculated year-over-year changes for each financial metric by creating new columns in the DataFrame that represent the percentage change from one year to the next.
- Explored other aggregate functions and groupings to analyze the data across different dimensions (by company, over years, etc.)


Documentation and submission:
- By using the markdown feature in Jupyter Notebook documented my methodology, observations, and conclusions throughout the notebook.
- After my analysis is complete, exported my Jupyter Notebook as a html file for submission to my manager. 
- This approach helped me focus on the core analytical aspects using pandas within a Jupyter Notebook, providing a clear, documented narrative of my financial analysis process. 
- By the end of this task, I have a comprehensive understanding of how to analyze financial data programmatically which is a valuable skill set for data-driven decision-making.
