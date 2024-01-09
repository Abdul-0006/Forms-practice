<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      body {
        background-color: rgb(143, 192, 211);
      }
      fieldset {
        color: rgb(0, 0, 3);
        border-color: rgb(19, 21, 22);
      }
    </style>
  </head>
  <body>
    <h1>User Registration Form</h1>
    <form>
      <div>
        <label for="Firstname"></label>First Name
        <input
          required
          type="text"
          id="Firstname"
          name="First Name"
          id="firstname"
        />
        <br />
        <br />
        <label for="Last Name"></label>

        Last Name
        <input
          id="Last Name"
          required
          type="text"
          name="Last Name"
          id="lastname"
        />
        <br />
        <br />
        <label for="password"> Password</label>
        <input
          required
          id="password"
          type="password"
          required
          name="Password"
          id="Password"
        />
        <br />
        <br />
        <label for="Bio"></label> Bio
        <textarea
          required
          id="Bio"
          name="Bio"
          id="bio"
          cols="30"
          rows="10"
        ></textarea>
        <br />
        <br />
      </div>

      <div>
        <fieldset>
          <legend>Gender</legend>
          <label for="Male"></label>
          <input required type="radio" name="Gender" id="Male" /> Male <br />
          <label for="Female"></label>
          <input required type="radio" name="Gender" id="Female" /> Female
          <br />
          <label for="Other"></label>
          <input required type="radio" name="Gender" id="Other" /> Other <br />
        </fieldset>
        <br />
        <fieldset>
          <legend>Interests</legend>
          <label for="Music"></label>
          <input type="checkbox" name="hobby" id="Music" /> Music <br />
          <label for="Sports"></label>
          <input type="checkbox" name="hobby" id="Sports" /> Sports <br />
          <label for="Reading"></label>
          <input type="checkbox" name="hobby" id="Reading" /> Reading <br />
        </fieldset>
      </div>
      <br />
      <br />
      <select name="Country" id="Country">
        <option required value="United States">United States</option>
        <option required value="Pakistan">Pakistan</option>
        <option required value="Russia">Russia</option>
        <option required value="United Kingdom">United KIngdom</option>
      </select>
      <br />
      <br />
      Preferred Colours
      <select name="Colours" id="Favcolour">
        <option required value="red">Red</option>
        <option required value="Blue">Blue</option>
        <option required value="Green">Green</option>
      </select>
      <br /><br />
      <input type="file" name="Image FILE" id="Img" accept=".png" />

      <br />
      <br />
      <label for="Dateofbirth"></label>
      Birthdate <input required type="date" name="Birthday" id="Dateofbirth" />
      <br />
      <br />
      <label for="EMAIL"></label>
      Email<input required type="email" name="Email" id="EMAIL" /><br />
      <br />
      <label for="weburl"></label>

      Website <input required type="url" name="Website" id="weburl" /><br />
      <br />
      <label for="Find"></label>
      Search <input required type="search" name="Search" id="Find" /> <br />
      <br />

      <input type="button" value="Submit" />
    </form>
  </body>
</html>
