# ILL-analysis
JMP script to to automate the creation of plots to visualize Interlibrary Loan data.

This .jsl file requires the statistical software JMP to run.  http://www.jmp.com

An example video of the .jsl file running on a dataset can be seen at https://www.screencast.com/t/iW4Thfg6


Plots created are:

--Frequency by Title

--Number of requests by Department

--Number of requests by Department, stacked by year

--Patron Status by Department

--Stacked bar chart by Lending Library

--Frequency by Publisher


For all plots to be correctly created, the .jsl file requires the following column names in your dataset.
Columns may be in any order, but must have the following capitalization:

--Year

--Department

--Status

--Loan Title

--Loan Publisher

--Lending Library
