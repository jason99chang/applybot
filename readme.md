# Job Applicator 

## Features: 
###     - Database - to keep track of jobs applied
            - Company name
            - Date Applied
            - Position Name
            - Status (not applied, applied, rejected, waiting for response, other)
            - Link
            
###    - Auto Applier - main program that will help make applying to jobs less repetative by autocompleting common fields
            - Console
                - Logs input taken, failed, applied, database updates, errors, and more.
            - Input File
                - File where all indeed links will be automatically filled out, applied, and put into the database
                - Any links that link to a job already applied to will be removed from the file
                - Jobs that were not successfully applied to will be marked with a "(!)" in the file and will not be removed
            - Resume
                - Resume is uploaded so that the bot can automatically upload it to indeed.
            - Profile File
                - Fill out profile for the bot to input information in the application website
            
            
