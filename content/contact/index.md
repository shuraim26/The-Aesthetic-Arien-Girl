+++
date = "2019"
title = "Get in Touch"
+++

<form method="post" name="contact" netlify>
    <p style="visibility:hidden;">
        <label>Bot Check</label>
        <input name=bot-field>
    </p>
    <label for="name">Name: </label>
    <br>
    <input type="text" id="name" name="name" placeholder="Enter your Name">
    <br>
    <br>
    <label for="email">Email: </label>
    <br>
    <input type="text" id="email" name="email" placeholder="Enter your Email Address">
    <br>
    <br>
    <label for="message">Message: </label>
    <br>
    <textarea type="text" id="message" name="message" placeholder="Open Up...." style="height:200px;"></textarea>
    <br>
    <br>
    <div data-netlify-recaptcha></div>
    <br>
    <br>
    <input type="submit" value="submit" style="">
</form>