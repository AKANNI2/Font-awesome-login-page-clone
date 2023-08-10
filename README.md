# Font-awesome-login-page-clone

Login Page with HTML and CSS Flexbox
This is a simple login page that was built with HTML and CSS Flexbox. The flexbox layout is used to center the form and align the form elements. The CSS also includes some basic styling for the form, such as setting the background color and font family.

HTML
The HTML for the login page is very simple. It consists of a div container for the form, and a form element with the following input elements:

input element for the username
input element for the password
button element for the login button
html
<div class="login-page">
<form action="/login" method="post">
<input type="text" name="username" placeholder="Username">
<input type="password" name="password" placeholder="Password">
<button type="submit">Login</button>
</form>
</div>

CSS
The CSS for the login page uses flexbox to center the form and align the form elements. The following CSS rules are used:

css
.card {
  padding: 2.4rem;
  background-color: #fff;
  box-shadow: 0 0 1.2rem 0 rgba(0, 0, 0, 0.2);
  border-radius: 1rem;

  display: flex;
  flex-direction: column;
}

.cta-form {
  margin-top: 2.8rem;
}


input[type="email"],
input[type="password"] {
  width: 100%;
  padding: 1.4rem 3.6rem;
  border: 0.2rem solid #475f74;
  border-radius: 0.8rem;
}


input[type="email"]:focus,
input[type="password"]:focus{
  outline: 0.4rem solid #99e9f2;

}

.placeholder-icon {
  position: absolute;
  top: 1.1rem;
  left: 1.2rem;
  font-size: 1.8rem;
  color: #193751;
}

input::placeholder {
  color: #ccc8c8;
  font-size: 1.2rem;
  font-weight: 500;
}

.checkbox-container{
  display: flex;
  align-items: center;
  justify-content: space-between;
}



Conclusion
This is a simple example of how to use HTML and CSS Flexbox to build a login page. The flexbox layout is a powerful tool that can be used to create responsive and visually appealing web pages.
