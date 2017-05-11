
# An introduction to Adabas and Natural programming
![alt text](https://cloud.githubusercontent.com/assets/25740455/25938714/7f4c321c-3630-11e7-9dca-db5877727731.jpg)

## Adabas

Short for "Adabtable Database"-- Adabas is the Comprehensive and scalable enterprise database management system optimized for big data and designed for reliability and high performance. It is available for mainframe, Linux®, UNIX® and Windows® (LUW) platforms.

More information here: http://www2.softwareag.com/corporate/products/adabas_natural/adabas/default.aspx


## Natural programming language

It is used in application development and deployment environment known for ease of-use, cross-platform portability and developer productivity. It is as well available for mainframe, Linux®, UNIX® and Windows® (LUW) platforms.

More information here: http://www2.softwareag.com/corporate/products/adabas_natural/natural/default.aspx


## Hello World ! in Natural
Now you can either have the option to check out our video tutorials  ~~here~~ or you try it out yourself by downloading the virtual machine ~~here~~

### Steps to using the virtual machine 
 * Download the Virtual machine image file from the TECHcommunity website (~~URL~~)
 * Run the 'Adabas and Natural' cheatsheets from Help menu
 * Explanation for the programs presented in the cheatsheets:
 
    - <b>First program: Hello World !</b>
      * <b>Description</b> : One of the many ways you can print your text/results on the screen is through the usage of the WRITE "string" statement
    - <b>Second program: Conditional constructs</b>
      * <b>Description</b> : The DECIDE ON statement is used to specify multiple actions to be performed depending on the value (or values) contained in a variable. Here, the FIRST keyword indicates that only the first value is to be processed with the NUMVALUE variable being initialised to 10. And therefore, based on the value contained in the NUMVALUE, an appropriate message is to be printed on the console, which is achieved through the usage of the DISPLAY statement here.
        
    - <b>Third program: Basic Array manipulation</b>
      * <b>Description</b> : This program illustrates the usage of the definition, initialisation, copy-to-another-array and print to the console operations.
         * Definition and initialisation of three 2-dimentional arrays.
         * Movement of the data from one array into another.
         * Two approaches to print the whole of the 2-dimensional arrays onto the console:
            * through nested loop
            * without the usage of the nested loop
        
   - <b>Fourth program: Adabas</b> : Retrieval of data from the database and print it on the screen
       * <b>Description</b> : This program shows an example of retrieval of data from the database
       * You would need to first, compile the data definition module CRUISE.NSD which contains the data fields 
       * The main program HISTOPGM.NSP would compute the total number of records in the Adabas file CRUISE for a specific START-HARBOR
       * Usage of REPEAT statement to initiate a processing loop, the exit condition for the loop would be a blank value for the START-HARBOR
       * Usage of ESCAPE statement to interrupt the linear flow of execution and exit the loop
 
### To explore more code samples....
  simply head over to the TECHcommunity... http://techcommunity.softwareag.com/ecosystem/communities/public/adanat/products/natural/codesamples/
 
### System Environment Requirement

 * Internet access
 * Windows 7 or higher
 * Adabas and Software AG designer (modules) pre-installed (provided as VM image) 
  

### If You Find Issues
Please report through an email to UniversityRelations@softwareag.com


### Notice
This tutorial only serves the purpose of introducing the concept of Adabas and Natural at a basic level of understanding
