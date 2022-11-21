## Access Package

This Will help the team to generate the predefined code for Access Package. 

## How to Use?
##### Type **accesspackage** and press tab on system

This will generate the output like


```
{ 
    "Name":"Access Package Name", 
    "SubscriptionID":"Subscription ID", 
    "CatalogName":"Catalog Name", 
    "TeamMemberPolicy":{ 
        "Groups": [ 
             "Group Name" 
          ],
        "Users": [ 
             "User Name" 
          ],
        "ReviewersGroup": [ 
             "Reviewers Group" 
          ],
        "ReviewersUsers": [ 
             "Reviewers Users" 
          ]
    },
     
    "NonTeamMemberPolicy":{ 
        "ApproversGroups": [ 
             "Group Name" 
          ],
        "ApproversUsers": [ 
             "User Name" 
          ],
        "ReviewersGroup": [ 
             "Reviewers Group" 
          ],
        "ReviewersUsers": [ 
             "Reviewers Users" 
          ]
    },  
    "Resources":[ 
       { 
         "Group": "Group Name", 
         "Role": "Group Name" 
      }    
  ],
    "ReplaceAccessPackage":"True",  
    "IsHidden":"True" 
}
```
### 1.0.2

Initial release of access-package
