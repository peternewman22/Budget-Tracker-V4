# Budget-Tracker-V4
The very first major project I started working on when I first started learning to code.
It's an experiment using dictionaries, json files, user input and pandas.
You upload a csv of your bank transcript and the program categorises them for you in a pandas dataframe using a keyword search of the descriptions in the transcript. It outputs an Excel file. 
Keyword : Subcategory mapping is stored in a json file eg: "TPG":"Internet"
Subcategory : Category mapping is stored in a separate json file eg: "Eating Out":{"Category":"Entertainment, "Class":"Expenditure"}
New keywords, subcategories and categories can be added on the fly.
Over time, the process of categorising your bank transcripts will get faster and faster as more keywords are added. Especially useful for recurring purposes.

V4 Features:
* Multiply matches are caught. The user is prompted to choose or add a new keyword.
* Skip option automatically adds "Uncategorised"

Features to be added:
* Remove or redefine keywords on the fly
* Keyboard input to skip (eg: Esc)

Stretch goals: 
* UI
