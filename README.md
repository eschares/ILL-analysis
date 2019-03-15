# ILL-analysis
JMP script to analyze ILL request data

This .jsl file requires the statistical software JMP to run.  http://www.jmp.com

It is intended to automate the creation of plots to visualize Interlibrary Loan data.

Plots created are:
--Frequency by Title
--Number of requests by Department
--Number of requests by Department, stacked by year
--Patron Status by Department
--Stacked bar chart by Lending Library
--Frequency by Publisher


For all plots to be correctly created, the .jsl file requires the following column names in your dataset.
Columns may be in any order, but must have the following punctuation:
--Year
--Department
--Status
--Loan Title
--Loan Publisher
--Lending Library
