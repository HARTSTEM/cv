# cv
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title> Index GTFO</title>
  </head>
  <body>
    <h1>Examples of Inputs for Reference</h1>
    <form class="" action="index.html" method="post">
        <!-- Below is an example of nesting the input element within the label element, removing the need to use 'for' or 'id' attributes -->
      <label>Add your comments
      <input type="text" name="Comments" value="">
      </label>
      <hr>
        <!-- Below is an example of using the 'for' and 'id' attributes, instead of the nesting method -->
      <label for="username">Enter your Username:</label>
      <input id="username" type="text" name="username" value="">
      <hr>
        <!-- When using the 'for' and 'id' attributes or the nested method with radio buttons (as shown below), the button can be activated by the user when they click on the text  -->
      <label for="gender">Is your gender male?</label>
      <input id="gender" type="radio" name="gender" value="">
      <hr>
      <label>Are you Australian?
      <input type="radio" name="australian" value="">
      </label>
      <hr>
      <label for="colour">Choose your favourite colour</label>
      <input type="color" id="colour" name="colour" value="">
      <hr>
      <label>Do you want free stuff?
      <input type="checkbox" name="free" value="">
      </label>

      <hr>
      <label>Choose your DOB
      <input type="date" name="DOB" value="">
      </label>
      <hr>
      <label>Select an image
      <input type="file" accept=".png, .jpg" name="image" value="" required="required">
      </label>
      <hr>
      <label>Subscribe
      <input type="email" name="subscribe" value="enter your email address" required="required">
      </label>
      <hr>
      <input type="submit" name="" value="Click to submit">
      <hr>
        <!-- The image input is used for graphical submit buttons -->
      <input type="image" name="image" src="images/submit graphic.png" width="150" height="auto">
      <hr>
      <label>Number counter
      <input type="number" name="number" value="">
      </label>
      <hr>
      <label>telephone
      <input type="tel" name="tel" value="">
      </label>
      <hr>
        <!-- In the Pasword field, the string entered by the client will be automatically hidden with ****** -->
      <label>Enter your password
      <input type="password" name="password" value="">
      </label>
      <hr>
      <label>Define the time
      <input type="time" name="time" value="">
      </label>
      <hr>
      <label>Date and time based on UTC time zone
      <input type="datetime-local" name="Date & Time" value="">
      </label>
      <hr>
      <label>Your Message
      <textarea name="Message" rows="10" cols="20"></textarea>
      </label>



    </form>


  </body>
</html>
