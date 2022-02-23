# K-Tags
Easy handling C-scope and C-tag symbols.

**Installation:**
- Clone the reprository with ```git clone git@github.com:Sansel-Tech/ktags.git```

Enter into the directory ```ktags``` and
- Do ```make build``` to install dependencies
- Do ```make install``` to install the application

**Usage:**
- Run ```ktags``` to build symbols in current directory
- Run ```cs``` to start cscope session

**Internals:**
- Running the command ```ktags``` will generate ```.ktags``` directory in the current path. This will contain the below three files for internal usage.
```
.ktags
  ├── cscope.files -- List of files the tags get generated
  ├── cscope.out   -- C-scope database
  └── tags         -- C-tag database
```
