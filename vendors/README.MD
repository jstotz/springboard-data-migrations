# Vendors
Import vendor records


## Required fields for import file
See sample file `vendors.csv`

* `Vendor #` (unique value, can be left blank to have Springboard auto assign)
* `Name` (unique value)
* `Address Line 1`
* `Address Line 2`
* `Address City`
* `Address State` (accepts state name or state abbreviation for US states)
* `Address Postal Code`
* `Country` (accepts 2 character country code of full country name)
* `Contact Office Phone`
* `Contact Email` (enforces email formatting of single address in standard format name@domain.com)
* any required custom vendor fields


## Import process

1. Create a CSV file with one line per vendor containing the columns listed above plus any additional field values specific to this client
2. Log into clients Springboard Retail account as an Admin
3. Navigate to `Purchasing => Vendors`
4. Click the `Import` button
5. Choose the CSV file created in step 1
6. Click `Upload` button to upload file to Springboard Retail
7. On the mapping screen we will map fields to their exact column name matches so all of the required fields listed above should have auto mapped
8. Click the `Complete Import` button to begin the vendor import


## Tips

* For source systems that have additional vendor contact details such as a first name, last name, or website, you can create custom fields to store these values.