# 📌 Forms in HTML

Forms are used to **collect user input**.

## ✅ Common Form Elements

* `<form>` → Defines form
* `<input>` → Text, Email, Password, Checkbox, Radio
* `<textarea>` → Multi-line text input
* `<select>` → Dropdown
* `<button>` / `<input type="submit">` → Submission

### 📝 Example

```html
<form action="submit.php" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="username"><br><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="useremail"><br><br>

  <label for="gender">Gender:</label>
  <input type="radio" name="gender" value="Male"> Male
  <input type="radio" name="gender" value="Female"> Female <br><br>

  <label for="course">Select Course:</label>
  <select id="course" name="course">
    <option value="html">HTML</option>
    <option value="css">CSS</option>
    <option value="js">JavaScript</option>
  </select><br><br>

  <input type="submit" value="Submit">
</form>
```

### 🎯 Output

* Name input field
* Email input field
* Gender radio buttons
* Dropdown for courses
* Submit button


