# event-registration-page 
<!DOCTYPR html>
<html>
  <body>
    <h1>Register Now</h1>
    <form>
      <label for='name'>Name:</label>
      <input type="text" id="name" name='name' placeholder='Enter your name'><br>
<br><br>
      <label for='email'>Email:</label>
      <input type='email' id='email' name='email' placeholder='Enter your email'>
<br><br>
      <label for='password'>Password:</label>
      <input type='password' id='passwordfield' name='passwordfield'>
<br><br>
      <label for="choose">Choose a session:</label>
      <select id="choose" name="choose">
        <option value="morning">Morning</option>
        <option value="afternoon">Afternoon</option>
      </select>
<br><br>
      <input type="checkbox" id="terms" name='checkboxgroup' value="terms">
      <label for="terms">I agree to the terms and conditions</label>
<br><br>
      <button type="submit">Submit</button>
    </form>
  </body>
</html>
