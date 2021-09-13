# Test Cases Samples

Below are some Test Case samples that I wrote while working on previous projects.

---------------------

**Description:**
Check if the login works when a person uses a correct user/pass.

**Steps to Reproduce**
1. Go to www.website.com/login
2. Add a correct user/pass
3. Press Login button

**Expected Result:**
User should be able to login and is taken to his profile page.

**Test Data:**
User:radu & Pass:123456

---------------------
**Description:**
Check if the login works when a person uses a wrong user/pass.

**Steps to reproduce**
1. Go to www.website.com/login
2. Add a wrong user/pass
3. Press Login button

**Expected Result:**
User should not be able to login. There will be an error message ”User or Password is wrong”

**Test Data:**
User: info & Pass: info1

------------------

**Description:**
Check if the login works when a person uses a correct user/pass and the Remember Me checkbox is on/pressed.

 **Steps to Reproduce**
1. Go to www.website.com/login
2. Add a correct user/pass
3. Press the Remember Me checkbox
4. Press Login button
5. Close the page
6. Go to login again

**Expected Result:**
User should be able to login and is taken to his profile page.
User should be able to acces his profile page without login credentials after he closes his profile page.

**Test Data:**
User:radu & Pass:123456

---------------------
**Description:**
Check if the login works when a person uses SQL Injection.

**Steps to Reproduce**
1. Go to www.website.com/login
2. Add a SQL Injection query
3. Press Login button

**Expected Result:**
User should not be able to login.

**Test Data:**
User: " or ""=" & Pass: " or ""="

-----------------------

**Description:**
Check if the search box is working by typing a product by it”s name.

**Steps to Reproduce:**
1. Go to emag.ro
2. Type a correct product name in the Search Box
3. Click on the Search Icon

**Expected Result:**
The user should be able to navigate through a result list displayed on the page.

**Test Data:** 
Insert: tricou de dama alb 

------------------------

**Description:**
Check if the search box is working by typing random letters.

**Steps to Reproduce:**
1. Go to emag.ro
2. Type some randome letters
3. Click on the Search Icon

**Expected Result:**
The page will display zero results with few advises:check if you spelled the term correctly; try using synonyms; try again, using a more general search.

**Test Data:** 
Insert: asasasa
