# Practical Codes and Resources for JDBC, JSP, and Servlet

Welcome to the repository for JDBC, JSP, and Servlet practicals! This repository contains useful resources and code examples to help you master these technologies.

## 📚 Resources

Find the detailed PDFs with explanations and guides below:

- [JDBC Guide](https://github.com/codewithz/YCMOU-TYBCA-Advanced-Java-Resources/blob/main/JDBC.pdf)
- [JSP Guide](https://github.com/codewithz/YCMOU-TYBCA-Advanced-Java-Resources/blob/main/JSP-Final.docx.pdf)
- [Servlet Guide](https://github.com/codewithz/YCMOU-TYBCA-Advanced-Java-Resources/blob/main/SERVLET.pdf)

# Practical List for Servlet, JSP, and Java

This repository contains practical activities to enhance your knowledge and skills in Servlet, JSP, and Java.

---

## Practical Activities

### **1. Servlet - I**
1. Write a servlet to determine whether the number is prime or not. <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/PrimeNumberServlet.java">Link for Practical</a>
2. Write a servlet to determine whether the entered name from the HTML form is a palindrome or not.<a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/PalindromeServler.java">Link for Practical</a> |  <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/webapp/name.html">Link for HTML</a> 
3. Write a servlet program to print all the even numbers between the two numbers entered by the user (e.g., user enters 5 and 500, so print even numbers between 5 and 500). <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/EvenNumberServlet.java">Link for Practical</a>

---

### **2. Servlet - II**
1. Write a servlet program where a user enters a name in a form, and you send back the length of the name to them.<a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/LengthServlet.java">Link for Practical</a> | <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/webapp/name-length.html">Link for HTML</a> 
2. Write an `HttpServlet` to accept the values for a table and insert them into it. <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/InsertMovieServlet.java">Link for Practical</a> | <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/webapp/movie2.html">Link for HTML</a> 
3. Write a servlet to fetch the movie at ID 9. <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/FetchMovieServlet.java">Link for Practical</a>
4. Write a servlet to fetch all the movies released between 3rd Jan 2015 and 3rd Jan 2016.

---

### **3. Servlet - III**
1. Write a servlet program to accept a number. If the number is even, redirect to `purplesq.com`; if the number is odd, redirect to `google.com`. <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/RedirectionServlet.java">Link for Practical</a>
2. Write a servlet program to redirect the request to another servlet, which requires a `String` as a parameter. The other servlet converts the string to lowercase. <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/ForwardingServlet.java">Link for Practical</a>
3. Write a Java program to get a name from an HTML form, store the name in a session, and redirect the flow to another servlet. The other servlet displays the name stored in the session. <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/AcceptNameServlet.java">Link for Practical 1 </a>  | <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/java/AnotherServlet.java">Link for Practical 2 </a>  |  <a href="https://github.com/codewithz/HindujaBCAPracticals/blob/master/src/main/webapp/name2.html">Link for HTML</a> 

---

### **4. JSP - I**
1. Write a JSP code to accept a number and determine whether the number is prime or not.
2. Write a servlet program to accept a `String` and determine whether the string’s length is greater than 6.
3. Write a JSP program to redirect to `Google.com`.

---

### **5. JSP - II**
1. Write a Java program to print the following pattern:


# JDBC Practical - Database Operations

This section contains practical activities focused on creating and querying databases using JDBC.

---

## **Practical Activities**

1. **Create the Database and Enter Sample Data**
   - Create a database with the following schema and sample data:
     | **Column Name** | **Data Type**  |
     |-----------------|---------------|
     | `id`            | `int`         |
     | `temp`          | `float`       |
     | `city`          | `varchar`     |
     | `precipitation` | `float`       |
     | `wind`          | `int`         |
     | `humidity`      | `float`       |
     | `date`          | `date`        |

     Sample data:
     ```
     id    temp    city    precipitation    wind       humidity     date
     1     25.5    Mumbai  3.0              25 km/hr   20%          2016-04-18
     ```

2. **Query to Show the Highest Temperature**
   - Retrieve the highest temperature for the city of Mumbai for the month of January 2016.
   <a href="https://github.com/codewithz/ycmou_bca_jdbc_practicals/blob/master/src/main/java/com/codewithz/HighestTemperature.java">Link for Practical</a>

3. **List Temperatures for Mumbai and Delhi**
   - List the temperatures for the cities of Mumbai and Delhi, sorted by their humidity (from lowest to highest).

4. **List Temperatures for Bangalore**
   - Retrieve the temperatures for the city of Bangalore for the month of February 2016.

5. **Show Days with Temperature Above 30°C**
   - Display all days where the temperature was above 30°C. Use a `Set` to store and display the unique results.

6. **List Temperatures by Precipitation for Bangalore**
   - List the temperatures for the city of Bangalore, sorted by their precipitation (from highest to lowest).

7. **Sort Temperatures by City Names**
   - Sort the list of temperatures according to the names of the cities.

---

**Spring Core and MVC**
   Repo Core: https://github.com/codewithz/hinduja-spring-core-app-jan-2025
   Repo MVC:  https://github.com/codewithz/hinduja-spring-mvc-app-jan-205
**Java Email**
   https://github.com/codewithz/hinduja-java-email-jan-2025



