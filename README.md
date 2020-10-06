# Google Sheet Script
Simple script for Google Sheets to be deployed as a web app to accept a POST request for filling data into a sheet.

## Requirements
1. Setup a Sheet with Row 1 containing columns matching the keys you'd like to store.
2. Save a new Script with this code and publish it as web app ( Tools -> Script Editor ).
3. Ensure web app is accessible to public.
4. Make a POST request with JSON data matching your header keys.
5. (Optional) - add a `Timestamp` column to automatically set a datetime when the POST was made
