# Restaurant inspection

## Data dictionary

|API field|Re-named field|Description|
|:-----|:-----|:-----|
|CAMIS|id|This is an unique identifier for the entity (restaurant)|
|DBA|name|This field represents the name (doing business as) of the entity (restaurant)|
|BORO|boro|Borough in which the entity (restaurant) is located. NOTE: There may be discrepancies between zip code and listed boro due to differences in an establishment's mailing address and physical location|
|BUILDING|building|This field represents the building number for the entity (restaurant)|
|STREET|street|This field represents the street name at which the entity (restaurant) is located|
|ZIPCODE|zipcode|Zip code as per the address of the entity (restaurant)|
|PHONE|phone|Phone Number|
|CUISINE DESCRIPTION|cuisineDescription|This field describes the entity (restaurant) cuisine.|
|INSPECTION DATE|inspectionDate|This field represents the date of inspection|
|ACTION|action|This field represents the actions that is associated with each restaurant inspection.|
|VIOLATION CODE|violationCode|This field represents the violation codes that is associated with each restaurant inspection.|
|VIOLATION DESCRIPTION|violationDescription|This field is the description that corresponds to the violation codes|
|CRITICAL FLAG|criticalFlag|This indicates if Violation is critical or not.|
|SCORE|score|Total Score for a particular inspection. If there was adjudication a judge may reduce the total points for the inspection and this field will have the update amount.|
|GRADE|grade| • N = Not Yet Graded • A = Grade A • B = Grade B • C = Grade C • Z = Grade Pending • P= Grade Pending issued on re-opening following an initial inspection that resulted in a closure|
|GRADE DATE|gradeDate|The date when the current grade was issued to the entity (restaurant)|
|RECORD DATE|recordDate|The date when the extract was run to produce this data set|
|INSPECTION TYPE|inspectionType|The type of inspection. A combination of the program and inspection type.|
