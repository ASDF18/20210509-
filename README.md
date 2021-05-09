# 20210509-

- form 사용법
action, method, enctype 


    <form action="demo_post_enctype.asp"method="post" enctype="multipart/form-data">
    First name: <input type="text" name="fname"><br>
    Last name: <input type="text" name="lname"><br>
    <input type="submit" value="Submit">
    </form>


-input 사용법
input 
   type : text, password, hidden, file, button, submit

    <h3>text</h3>
    <input type="text" name="myname">
    <hr>
    
    <h3>password</h3>
    <input type="password" name="pwd">
    <hr>
    
    <h3>hidden</h3>
    <input type="hidden" name="country" value="Norway">
    <hr>
    
    
    <h3>file</h3>
    <input type="file" name="myfile">
    <hr>
    
    <h3>button</h3>
    <input type="button" value="Click me" onclick="alert('Hello world!')">
    <hr>
    
    
    
    <h3>submit</h3>
    <input type="submit" value="Submit">
    <hr>
    
-textarea 사용법

    <!DOCTYPE html>
    <html>
    <body>
    <textarea name="message" rows="10" cols="30">Write something here</textarea>
    </body>
    </html>
    
-select 사용법
    
     <select name="cars2" size="4" multiple>
     <option value="volvo">Volvo</option>
     <option value="saab">Saab</option>
     <option value="fiat">Fiat</option>
     <option value="audi" selected>Audi</option>
     </select>

     <select name="cars3">
     <optgroup label="Swedish Cars">
     <option value="volvo">Volvo</option>
     <option value="saab">Saab</option>
     </optgroup>
     <optgroup label="German Cars" disabled>
     <option value="mercedes">Mercedes</option>
     <option value="audi">Audi</option>
     </optgroup>
     </select>
    
-button 사용법
     type : button, submit, reset
     checkbox 
     <!DOCTYPE html>
     <html>
     <body>
     <button type="button" onclick="alert('Hello World!')">Click Me!</button>

     <input type="button" value="Click Me!" onclick="alert('Hello world!')">
     </body>
  
     <button type="submit" name="myButton" value="foo">Click me</button>
     <h3>checkbox</h3>
     
     <h3>reset</h3>
     <input type="reset">
     <hr>
     </html>
     
     <input type="checkbox" name="fruit1" value="apple" checked> 사과<br>
     <input type="checkbox" name="fruit2" value="grape"> 포도<br>
     <input type="checkbox" name="fruit3" value="peach"> 복숭아<br>
     <hr>

    
-radion 사용법

    <h3>radio</h3>
    <input type="radio" name="gender" value="male" checked> 남자<br>
    <input type="radio" name="gender" value="female"> 여자<br>
    <hr>
    
    
-a 사용법

    <a href="https://www.w3schools.com">Visit W3Schools.com!</a>


-ul 사용법
    <ul>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
    </ul>


-li 사용법

   <ul>
   <li>Coffee</li>
   <li>Tea</li>
   <li>Milk</li>
   </ul>
