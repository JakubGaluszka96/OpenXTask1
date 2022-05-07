# Task 1
Test function and create input/output data sets, describe which cases this data set will test:
___
## Answer:
|Input             |Output|Description                           |
|------------------|------|--------------------------------------| 
|abcabcbb          |3     |Basic happy path                      |
|aaaaaaaa          |1     |Checking equal symbols case           |
|abcdefghijklmnop  |16    |Checking case w/o repeating characters|
|                  |0     |Checking empty string                 |
|abbcdb            |3     |Substring unequal to subsequence      |
|ABCabcABC         |6     |Capital letter detection              |
|12341334433       |4     |Checking numbers                      |
|abcd efg hij      |8     |Checking space detection              |