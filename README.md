## 🟠 Level 6 — HTML Forms

HTML Forms are used to collect information from users, such as name, email, password, age, gender, files, messages, and more.

### 📌 Topics Covered

1. **Form — `<form>`**
   Used to create an HTML form.

2. **Input — `<input>`**
   Used to create input fields for collecting user information.

3. **Input Type — `type`**
   Defines the type of input field.

4. **Name — `name`**
   Gives a name to the input data.

5. **Placeholder — `placeholder`**
   Shows a hint inside an input field.

6. **Label — `<label>`**
   Provides a label or description for an input field.

7. **Text Input**
   Used to collect normal text such as a user's name.

8. **Password Input**
   Used to collect passwords. The entered characters are hidden.

9. **Email Input**
   Used to collect email addresses.

10. **Number Input**
    Used to collect numerical values.

11. **Radio Button**
    Allows the user to select one option from a group.

12. **Checkbox**
    Allows the user to select one or multiple options.

13. **File Input**
    Allows the user to select a file from their device.

14. **Select — `<select>`**
    Used to create a dropdown menu.

15. **Option — `<option>`**
    Defines an individual option inside a dropdown menu.

16. **Textarea — `<textarea>`**
    Used to enter multiple lines of text, such as messages or comments.

17. **Button — `<button>`**
    Used to create a clickable button.

18. **Submit Button**
    Used to submit the form data.

### 💻 Example

```html
<form>

    <!-- Text Input -->
    <label for="name">Full Name:</label>
    <input
        type="text"
        id="name"
        name="name"
        placeholder="Enter your name"
    >

    <br><br>

    <!-- Email Input -->
    <label for="email">Email:</label>
    <input
        type="email"
        id="email"
        name="email"
        placeholder="Enter your email"
    >

    <br><br>

    <!-- Password Input -->
    <label for="password">Password:</label>
    <input
        type="password"
        id="password"
        name="password"
        placeholder="Enter your password"
    >

    <br><br>

    <!-- Number Input -->
    <label for="age">Age:</label>
    <input
        type="number"
        id="age"
        name="age"
        placeholder="Enter your age"
    >

    <br><br>

    <!-- Radio Button -->
    <p>Gender:</p>

    <label>
        <input type="radio" name="gender" value="male">
        Male
    </label>

    <label>
        <input type="radio" name="gender" value="female">
        Female
    </label>

    <br><br>

    <!-- Checkbox -->
    <p>Skills:</p>

    <label>
        <input type="checkbox" name="skills" value="html">
        HTML
    </label>

    <label>
        <input type="checkbox" name="skills" value="css">
        CSS
    </label>

    <label>
        <input type="checkbox" name="skills" value="javascript">
        JavaScript
    </label>

    <br><br>

    <!-- File Input -->
    <label for="photo">Upload Photo:</label>
    <input
        type="file"
        id="photo"
        name="photo"
    >

    <br><br>

    <!-- Select & Option -->
    <label for="country">Country:</label>

    <select id="country" name="country">
        <option value="bd">Bangladesh</option>
        <option value="in">India</option>
        <option value="pk">Pakistan</option>
        <option value="us">USA</option>
    </select>

    <br><br>

    <!-- Textarea -->
    <label for="message">Message:</label>

    <textarea
        id="message"
        name="message"
        rows="5"
        cols="30"
        placeholder="Write your message"
    ></textarea>

    <br><br>

    <!-- Submit Button -->
    <button type="submit">Submit</button>

</form>
```

### 📝 What I Learned

* How to create HTML forms
* How to use different input types
* How to use labels and placeholders
* How to create text, email, password, and number inputs
* How to use radio buttons and checkboxes
* How to add file input
* How to create dropdown menus
* How to use `<textarea>`
* How to create buttons
* How to submit form data

**Level 6 Completed ✅**
