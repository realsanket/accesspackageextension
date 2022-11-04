## Access Package

This Will help the team to generate the predefined code for Access Package. 

## How to Use?
##### Type **accesspackage** and press tab on system

This will generate the output like


```

{ 
    "Name":"Access Package Name", 
    "Description":"Access Package Description", 
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
    } 
     
}
```
### 1.0.2

Initial release of access-package
