Weight Converter Manual
======================

Liang Zhou
lzhou86@gatech.edu

----------

Introduction
-----------------

This app is used to convert weights between different units including **stones**, **pounds**, **ounces**, **grains**, **metric tons**, **kilograms**, **grams**,  and **milligrams**.

This app includes two drop down menu: **Convert from** and **Convert to**. You are free to choose any unit that you are interested in, and both of them  default to **Stones**. You are allowed to type a number in the text field **Value**. The number in the selected unit in **Convert from**  will be convert into the a number in the selected unit in **Convert to**,  and the converted number will be output in the text field **Result**.

There are three buttons in the lowest part of this app: **CONVERT**, **RND CONVERT**, and **RESET**.  **CONVERT** is used to execute the conversion between both selected units. **RND CONVERT** is used to execute a conversion with the random destination unit. In other words, it will randomly choose a unit for you. **RND CONVERT** will also set **1**  as the value for you if you type into nothing.


Requirement
------------------
This app should run on an android phone or tablet supporting android SDK API Level 15 or above.


Usage Example
----------------------

**Convert Kilograms to Pounds**

>Step 1: select **Kilograms** from the first drop down menu as your original unit;
Step 2: select **Pounds** from the second drop down menu as your destination unit;
Step 3: press or touch the first line and input  a number, for example 4.05, as your value;
Step 4: press or touch **CONVERT**, the converted result will be displayed above the line behind **Result**.

**Convert Grams to a random unit**

>Step 1: select **Grams** from the first drop down menu as your original unit;
Step 2: press or touch the first line and input  a number, for example 1.8, as your value;
Step 4: press or touch **RND CONVERT**. It randomly chooses a destination unit for you and set it in the second drop down menu, at the same time the converted result will be displayed above the line behind **Result**.
>> **Note:** If you don't type in any number, **RND CONVERT** still works since it automatically sets **1** as your value;

**Reset**

Step 1: press or touch "RESET", it will reset to the default state
