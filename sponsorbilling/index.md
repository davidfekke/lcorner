---
layout: page
title: "Finish Joining as a Sponsor"
description: ""
---

<div class="container">
    <form class="form">
        <label for="inputUsername" class="sr-only">Email address</label>
        <input type="username" id="inputUsername" class="form-control" placeholder="Username" required autofocus />
        <br />
        <label for="inputEmail" class="sr-only">Email address</label>
        <input type="email" id="inputEmail" class="form-control" placeholder="Email address" required autofocus />
        <br />
        <label for="inputPassword" class="sr-only">Password</label>
        <input type="password" id="inputPassword" class="form-control" placeholder="Password" required>
        <br />
        <label for="inputConfirmPassword" class="sr-only">Password</label>
        <input type="password" id="inputConfirmPassword" class="form-control" placeholder="Confirm Password" required>
        <br />
        <button class="btn btn-lg btn-primary btn-block" onclick="location.href='{{ site.baseurl }}/billinginfo/'">Sign in</button>
    </form>
</div>

Move to another screen to capture billing information and creation of profile aka username password.  Generates unique ID.  
Redirect - Once complete they will now be directed to the Subscribers/Sponsors Page
