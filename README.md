# dividend_data_google_sheets
With this code you can get dividend data, and this data is uploaded automatically to specified google sheet  
![image](https://github.com/jcalienni/dividen_data_google_sheets/assets/53088875/eef750e4-ee66-437e-8fce-6ea5385e9e13)


Need polygon.io account. Free trial allows 5 api requests per minute  
Need google cloud and activate googlesheet API. need to generate credentials json file from google cloud  
Rename json credentials file to "credentials.json" and add it to project root  

Requirements  
pip install -r requirements.txt  
Inside .env file you should add the following information:  
SPREADSHEET_ID = "you_spread_sheet_id"  
POLYGON_IO_API_KEY = "your_polygon_io_api_key"  
