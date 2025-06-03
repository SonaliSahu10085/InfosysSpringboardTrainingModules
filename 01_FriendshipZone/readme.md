# 💖 Friendship Zone Web Application

Friendship Zone is a web application, where an individual can connect with his/her friends. Refer to the below-listed details for creating a Friendship Zone application.

Create below mentioned HTML page(s) with listed features:

- 🏠 **Homepage.html** - For displaying Friendship Zone Home page  
- 📋 **FriendList.html** - For displaying details of people already available at Friendship Zone  
- 📝 **RegistrationForm.html** - For displaying the form to enroll yourself at Friendship Zone  
- ✅ **RegistrationConfirmation.html** - For successful registration of the user  
- 🛡️ **RegistrationConfirmationforAdmin.html** - For successful registration of admin  

---

## 🏠 1. Homepage.html - For displaying Friendship Zone Home

**Features to be implemented:**

- 🧩 Use appropriate sectioning element(s) to give meaning to the content  
- 🔍 "Click to Search Friends" should take the user to `friend-list.html`  
- 🌐 Use appropriate element(s) to display Facebook and Twitter links  

---

## 📋 2. FriendList.html - For displaying details of people already available at Friendship Zone

**Feature(s) to be implemented:**

- 📊 Use appropriate element(s) to display a table containing details of people  
- 📝 "Register to get added to the list" should take the user to `registration.html`  
- 📎 Other links and buttons as mentioned in the screenshot are for display purpose only  

---

## 📝 3. RegistrationForm.html - For displaying the form to enroll yourself at Friendship Zone

**Feature(s) to be implemented:**

1. 🧾 Use appropriate element(s) to create a form  
2. 🛠️ Implement validations for each form field as mentioned below:

| 🏷️ **Field** | ✅ **Validation** |
|--------------|------------------|
| **Name** 👤 | - It is a mandatory field, only for user  <br> - Should not be less than 3 characters and should not contain any numbers |
| **Email** 📧 | - Valid format of the email should be entered |
| **Age** 🔢 | - Individuals below the age of 18 are not allowed to register <br> - It should accept only digits |

For all other form fields, maintain the look and feel of the application as per the above-given screenshot.

- 🟢 The **"Register"** button should take the user to `RegistrationConfirmation.html`, ensuring successful validations for all form fields.  
- 🔵 The **"Register as Admin"** button should take the user to the `RegistrationConfirmationforAdmin.html` page, irrespective of successful validations.  
- 🔗 Registration Confirmation pages for both admin and user should have a link to go back to the `Homepage.html` page.

---

## ✅ 4. RegistrationConfirmation.html – For the successful registration of a user

**Feature(s) to be implemented:**

- 🎉 Display a successful registration message to the user  
- 🔙 Provide a link to `Homepage.html`  

---

## 🛡️ 5. RegistrationConfirmationforAdmin.html – For successful registration of admin

**Feature(s) to be implemented:**

- 🎉 It should display a successful registration message to the admin  
- 🔙 Provide a link to `home.html`  
