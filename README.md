
# Mongodb Database Import and Export

## Youtube Video Link

    [Youtube](https://www.youtube.com/watch?v=vofx6XSFjsM)

                Or

## Install A Tool For Mongodb database

    1) Search the MongoDB Command Line Database Tools Download 
                or ( scroll down and find the link )
        [Download page Link ](https://www.mongodb.com/try/download/database-tools)
    2) Download the msi package
    3) Install the file  

## Create a folder in Desktop

    1) Open the folder and copy the path

## Open a cmd 

    Go to the path 
    eg: C:\Users\MACBOOK AIR\Desktop\ct> ( you see link this in termial )

## Export The Hole Database Use This Command

    1)  ```bash
            mongodump
        ```
    2) Go and open a created folder 
    3) And you see the dump folder
    4) open the folder you got the enter Database

## Export The Single Doc Use This Command

    1)  ```bash
            mongodump -d CryptoBazaar --out doc
        ```
        -d : Directory Name
        -out : OutPut Folder Name
    2) Go and open a created folder 
    3) And you see the doc folder
    4) Open the folder you find a single Database

## Restore The Single File In Database

    1)  ```bash
            mongorestore doc ( doc means Name Of The Folder )
        ```

