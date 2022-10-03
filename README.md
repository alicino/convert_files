# README

#### General Orientation

Scripts for helping converting files from some extensions, such as json, xml, or csv to another.

The two scripts have the same content, but for different files to provide a paralelism in execution.

***

### Script convert_agent.py

Source file agent_status2.json (in this example)
Outuput file agent_status.csv

### Script convert_services.py

Source file services_x.json (in this example)
Outuput file services.csv

Note: I did not have a good format in this file, so I had to execute a sed command to include commnas (",") within this file separeting colummns. 

Command:
```bash
sudo sed 's/}/},/g' services2.json > services_x.json 
```

---

A guide about convertion here:
<https://www.geeksforgeeks.org/convert-json-to-csv-in-python/>