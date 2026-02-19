---

## 📝 HTML Forms

HTML forms are used to collect user input.

---

## 🛠 Basic Form Structure

<form>
  <input type="text">
</form>

---

## ⭐ Common Form Elements

### 1️⃣ Text Input

<input type="text" placeholder="Enter your name">

---

### 2️⃣ Email Input

<input type="email" placeholder="Enter your email">

---

### 3️⃣ Password Input

<input type="password" placeholder="Enter password">

---

### 4️⃣ Radio Button

<input type="radio" name="gender"> Male
<input type="radio" name="gender"> Female

---

### 5️⃣ Checkbox

<input type="checkbox"> I agree to terms

---

### 6️⃣ Textarea

<textarea placeholder="Write your message"></textarea>

---

### 7️⃣ Dropdown (Select)

<select>
  <option>Option 1</option>
  <option>Option 2</option>
</select>

---

### 8️⃣ Submit Button

<button type="submit">Submit</button>

---

## 🎯 Example Complete Form

<form>
  <label>Name:</label>
  <input type="text" placeholder="Enter your name"><br><br>

  <label>Email:</label>
  <input type="email" placeholder="Enter your email"><br><br>

  <label>Password:</label>
  <input type="password" placeholder="Enter password"><br><br>

  <button type="submit">Register</button>
</form>

---

## 🧠 Important Attributes in Forms

- action → where form data goes
- method → GET or POST
- required → makes field mandatory
- name → important for backend

Example:

<form action="/submit" method="POST">
