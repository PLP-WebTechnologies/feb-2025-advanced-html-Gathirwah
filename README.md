# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Working on attribute</title>
</head>
<body>
 <!--Add an ordered list with roman numerals-->
 <ol>
    <li>English</li>
    <li>Science</li>
    <li>Mathematics</li>
    <li>Geography</li>
 </ol>
    <br> <br>
<!--Add an external image from pexels.com-->

<img src="" alt="A black cat">
<br> <br>

<!--Add a table of 5 contacts with; name, address, mobile and emails-->
<table>
    <thead>
        <td>Name</td>
        <td>Address</td>
        <td>Mobile</td>
        <td>Email</td>
    </thead>
    <tbody>
        <tr>
            <td>Mikoh</td>
        <td>567 Thika</td>
        <td>0735666444</td>
        <td>mikoh35@gmail.com</td>
        </tr>
        
<tr>
        <td>Michelle</td>
        <td>082 Maldives</td>
        <td>073455555</td>
        <td>miche23@gmail.com</td>
    </tr>

    <tr>
        <td>Jossy</td>
        <td>21 Masoliny</td>
        <td>0734453224</td>
        <td>jossy15@gmail.com</td>
    </tr>

    <tr>
        <td>Nawel</td>
        <td>86 Martiny</td>
        <td>073359246</td>
        <td>nawel95@gmail.com</td>
    </tr>

<tr>
    <td>Trevor</td>
    <td>394 Lagos</td>
    <td>01855464934</td>
    <td>trevor79@gmail.com</td>
</tr>

    </tbody>
</table>

<br> <br>

<!-- Add a registration form-->

<h2>Registration Form</h2>

<hr>

<form action="">
<label for="name"> Name
<input type="text" placeholder="Full Name">
</label>
<br>  <br>

<label for="email"> Email
<input type="email" placeholder="johndoe@gmail.com">
</label>
<br>  <br>

<label for="password"> Password
<input type="password" placeholder="password">
</label>
<br>  <br>

<label for="date"> Date
<input type="date">
</label>
<br> <br>


<br> <br>

<input type="submit" value="Register">
</form>


</body>
</html>















