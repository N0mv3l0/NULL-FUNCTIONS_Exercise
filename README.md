# NULL-FUNCTIONS_Exercise

Extra practice exercise from BrightLearn portal

The repository includes the following files:

--The original exercise questions downloaded from the Brighlearn portal.

-- A pdf of solutions 

-- The SQL script of class notes of NULL FUNCTIONS.


What I learned: 

NULL: -- DESCRIBES AN EMPTY SPACE/ NO VALUE RETURNED/MISSING VALUE FROM THE DATASET
NULL FUNCTIONS: -- Help us to deal with NULL values from our dataset

How do we know that we have a NULL value in the data?

USE IS NULL FUNCTION.

-- This function helps us to find the NULL value.
-- OR a row of a specific column that has a NULL value

How do I find values that are not NULL?

USE 'IS NOT NULL FUNCTION':-- This is the opposite of IS NULL
            -- A way to find the rows where a specific column is not empty


How to replace a NULL value?

- USE 'IF NULL FUNCTION': -- REPLACES A NULL VALUE WITH A DEFAULT OR ALTERNATE VALUE OF YOUR CHOICE.
-- IF NULL(expression, default_value)
-- FOUND WITHIN YOUR SELECT STATEMENT
        

COALESCE() AND IF NULL -- SIMILAR, BUT THE COALESCE REPLACES THE NULL VALUE WITH MULTIPLE OPTIONS.
-- COALESCE(expr1, expr2, expr3...exprN)
-- Can check multiple columns and replace the first NULL value
-- Also used in the SELECT statement


