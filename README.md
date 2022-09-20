# DMW
Repository that contains course material to understand Data Management &amp; Warehousing

# Instructions for Lab test no. 1
### Submit your sql query file in **L1_Your_Name.txt** file format in Google Classroom assignment

----
Level-1 queries

-----
1. Create a database with name `e_shopping`
2. Create **2** tables `buyers` & `sellers`
with **3** attributes `id`, `name` & `dob` in both tables (`buyers` & `sellers`) with following rules (Point no. **3** to **6**)
3. `id` attribute is of *integer* data type and can not be null
4. `name` attribute is of *varchar* data type with length **20** and it can not be null
5. `dob` attribute is of *date* data type
6. `id` shall be the *primary KEY*

-----
Level-2 queries

-----

7. Populate your table with **500** unique tuples/records following above schema
8. change table structure by adding 1 more column/attribute with the name `age` of int data type
9. calculate the `age` using `dob` for each tuple and assign the value to `age` attribute for each tuple
10. display the maximum value of age in buyers table
