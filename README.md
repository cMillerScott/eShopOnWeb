Affirma Code Challenge

Friday night:
-explored codebase
-located CatalogItem.cs in src/ApplicationCore/Entities
Basket.cs in src/ApplicationCore/Entities/BasketAggregate.

Saturday morning:
-read through readme.md
-explored other documentation including video and ebook
-forked project to personal repo
-cloned repo into VS
-built and ran web app from VS
-ran public api from power shell
-took break/walked dogs

Saturday afternoon:
-Encountered browser error involving “access-control-allow-origin” missing in CORS header when attempting to access Manage Product Catalog from Admin account
-Continued reviewing application file structure to determine best way to accomplish assigned tasks
-Added “subtitle” field to CatalogItem entity
-Followed build errors to add “subtitle” to other areas needing the field
-Encountered “sql column” error

Sunday morning:
-Corrected db error with correct Ef migration commands through power shell
-Began work toward adding subtitle info to pages and views
-Ran into issue where database seed info wouldn’t post subtitle data to website


Sunday Afternoon:
-Determined I could manually enter subtitle data from admin page and edited data was persistent
-Attempted altering basket views to include subtitle, but adding that data messed up the styling
-Began task 3
-Discovered onchange=“this.form.submit()” method to accomplish task 3
-Added "Delete All" button to /Basket/index.html
-Broke user basket by having button post to nonexisting "Delete" endpoint
-Troubleshot issue by recalibrating /Basket/index.html to original codebase
-Issue persists...
