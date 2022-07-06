<!DOCTYPE html>
<html lang ="en">
<head>
  <title> My Travel Site</title>
</head>
<body>
    <!--  -->
    <!-- h tags range from 1 to 6; 1 being the largest and 6 being the smallest -->
    <h1>Welcome to my Travel Site</h1>
    <p>This site is all about where I want travel</p>
    <!-- p tag - Paragraph tag -->
    <h2>Here are some places I'd like to visit</h2>
    <ol>
        <!-- list item tag -->
        <li>Spain</li>
        <li>Italy</li>
        <li>Aruba</li>
        <li>Alaska</li>
    </ol>
    <ul>
        <!-- Links are represented by the anchor tag a -->
        <!-- <a href="#"target="_blank">Click Me</a> -->
        <li>
        <img src="https://upload.wikimedia.org/wikipedia/en/9/9a/Flag_of_Spain.svg" width="50">
        <a href="http://www.spain.info/en_US/" target="_blank">Spain</a>
        </li>
        <li>
        <img src="https://upload.wikimedia.org/wikipedia/en/0/03/Flag_of_Italy.svg" width="50">
        <a href="http://www.italia.it/en/home.html" target="_blank">Italy</a>
        </li>
        <li>
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f6/Flag_of_Aruba.svg" width="50">
        <a href="http://www.arubatourism.com/" target="_blank">Aruba</a>
        </li>
        <li>
        <img src="https://upload.wikimedia.org/wikipedia/en/a/a4/Flag_of_the_United_States.svg" 
                 width="50">
        <a href="https://www.travelalaska.com/" target="_blank">Alaska</a>
        </li>
    </ul>
    <!-- Table element -->
<table>
    <!-- Table row -->
    <tr>
      <th>Destination</th>
      <th>Capital</th>
      <th>Official Language</th>
    </tr>
    <tr>
      <td>Spain</td>
      <td>Madrid</td>
      <td>Spanish</td>
    </tr>
    <tr>
      <td>Italy</td>
      <td>Rome</td>
      <td>Italian</td>
    </tr>
    <tr>
      <td>Aruba</td>
      <td>Oranjestad</td>
      <td>Dutch</td>
    </tr>
    <tr>
      <td>Alaska</td>
      <td>Juneau</td>
      <td>n/a</td>
    </tr>
    <!-- This is where our list ended -->
  </table>
<!-- HTML Forms -->
    <!-- Allows you to get info from your users -->
    <!-- Used to label form inputs -->
    <form>
        <label for="name">Name: </label>
        <input type="text" id="name" name="name"><br>
        <p>Select any that apply:</p>
        <label for="spain">Spain</label>
        <input type="checkbox" id="spain" name="spain"><br> 
        
        <label for="france">France</label>
        <input type="checkbox" id="france" name="france"><br>

        <label for="portugal">Portugal</label>
        <input type="checkbox" id="portugal" name="portugal"><br>

        <label for="china">China</label>
        <input type="checkbox" id="china" name="china"><br>
    </form>
    <br><br>
    <textarea id="bio" name="bio" rows="7" cols="50">
    Tell me a bit more about the place you'd love to visit.
    </textarea>
    <br><br>
    <input type=submit value="Ok Go!">
    <input "type">What is your favorite type of travel locations?</label>
    </form>
    <!-- <form>
        <label for="name">Name </label>
        <input type="text" id="name" name="name"/>
        <p>Select any that apply</p>
       <br> -->
</body>
</html>

