---
layout: page
title: "Billing Info"
description: ""
---

<div class="container">
    <form class="form">
        <label for="inputCreditCardNumber" class="sr-only">Credit Card Number</label>
        <input type="username" id="inputCreditCardNumber" class="form-control" placeholder="Credit Card Number" required autofocus />
        <br />
        <label for="inputBillersFullName" class="sr-only">Your name on your credit card</label>
        <input type="text" id="inputBillersFullName" class="form-control" placeholder="Your name on your Credit Card" required autofocus />
        <br />
        <label for="inputSecurityCode" class="sr-only">SecurityCode</label>
        <input type="text" id="inputSecurityCode" class="form-control" placeholder="Security Code" required autofocus />
        <br />
        <label for="inputExpirationDate" class="sr-only">Expiration Date</label>
        <input type="date" id="inputExpirationDate" class="form-control" placeholder="Expiration Date" required autofocus />
        <br />
        <br />
        <label for="inputBillingAddress" class="sr-only">Billing Address</label>
        <input type="text" id="inputBillingAddress" class="form-control" placeholder="Billing Address" required autofocus />
        <br />
        <label for="inputBillingAddress2" class="sr-only">Billing Address</label>
        <input type="text" id="inputBillingAddress2" class="form-control" placeholder="additional Billing Address" required autofocus />
        <br />
        <label for="inputCity" class="sr-only">Billing City</label>
        <input type="text" id="inputCity" class="form-control" placeholder="City" required autofocus />
        <br />
        <label for="inputState" class="sr-only">Billing State</label>
        <input type="text" id="inputState" class="form-control" placeholder="State" required autofocus />
        <br />
        <label for="inputZip" class="sr-only">Billing Zip</label>
        <input type="text" id="inputState" class="form-control" placeholder="Zip" required autofocus />
        <br />
        <button class="btn btn-lg btn-primary btn-block" onclick="location.href='{{ site.baseurl }}/'">Purchase membership</button>
    </form>
</div>