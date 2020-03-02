---
ID: 3219
post_title: Contact
author: Bryan Richards
post_excerpt: ""
layout: page
permalink: >
  http://sandbox.yorebridgehouse.co.uk/contact/
published: true
post_date: 2019-07-30 11:05:42
---
<div class="row map-contact-row row-has-bottom-border columns-wrapper">
<div class="column-one-half contact-column">
<div class="content-padding">
<h4>Contact Yorebridge</h4>
If you would like to contact Yorebridge House for any reason, please either call us on the number below or email us using the form opposite.

<b>Bookings: </b>
+44 (0)1969 652060
<a href="#">enquiries@yorebridgehouse.co.uk</a>

<b>Address</b>
Yorebridge House,
Bainbridge,
North Yorkshire Dales,
Great Britain,
DL8 3EE

<b>Directions</b>
For directions to the hotel please use <a href="https://goo.gl/maps/kWCTELZzwdD2">this link</a>.

</div>
</div>
<div class="column-one-half contact-column">
<div class="content-padding"><form id="quote_form" role="form" action="" method="post">
<div class="form_row">
<div class="column-one-half">
<div class="form-group"><label for="first_name">First Name *<span class="wpcf7-form-control-wrap your-name"><input id="first_name" class="form-control" name="form_name" pattern="[A-Za-z][A-Za-z\s]{2,}" required="true" type="text" oninvalid="this.setCustomValidity('First Name should be min 3 alphabets')" oninput="this.setCustomValidity('')" /></span></label></div>
</div>
<div class="column-one-half">
<div class="form-group"><label for="last_name">Last Name *<span class="wpcf7-form-control-wrap your-name"><input id="last_name" class="form-control" name="form_lastname" pattern="[A-Za-z][A-Za-z\s]{2,}" required="true" type="text" oninvalid="this.setCustomValidity('Last Name should be min 3 alphabets')" oninput="this.setCustomValidity('')" /></span></label></div>
</div>
</div>
<div class="form_row">
<div class="column-one-half">
<div class="form-group"><label for="email">Email *<span class="wpcf7-form-control-wrap your-name"><input id="email" class="form-control" name="email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.(COM|ORG|UK|CO.UK|ORG.UK|NET|INFO|info|net|org.uk|co.uk|uk|org|com)$" required="true" type="email"   oninvalid="this.setCustomValidity('Please use a valid Email address, ending with .uk; .co.uk; .com ;.org ;.org.uk ;.net ;.info')" oninput="this.setCustomValidity('')"/></span></label></div>
</div>
<div class="column-one-half">
<div class="form-group"><label for="phone">Phone *<span class="wpcf7-form-control-wrap your-name"><input id="phone" class="form-control" name="phone" pattern="[0-9]{8,13}" required="true" type="tel" oninvalid="this.setCustomValidity('Contact Number must contain 8-13 digits phone numbers only')" oninput="this.setCustomValidity('')" /></span></label></div>
</div>
</div>
<div class="form_row">
<div class="column-one-half">
<div class="form-group"><label for="form_service">Service *
<select id="form_service" class="" name="service" required="true" oninvalid="this.setCustomValidity('Please select one of the Services listed below')" oninput="this.setCustomValidity('')"  onchange="test_fn(this)">
<option selected="selected" value="">- Select a Service -</option>
<option id="houserooms" value="House Rooms">House Rooms</option>
<option id="hottubrooms" value="Hot Tub Rooms">Hot Tub Rooms</option>
<option id="restaurant" value="Restaurant">Restaurant</option>
<option id="tastingroom" value="Grand Siècle Tasting Room">Grand Siècle Tasting Room</option>
<option id="weddings" value="Weddings">Weddings</option>
<option id="special" value="Special Offers">Special Offers</option>
<option id="events" value="Events">Events</option>
<option id="general" value="General Enquiries">General Enquiries</option>
</select></label></div>
</div>
</div>
<div class="form_row">
<div class="self_mail_txt">
<div class="form-group"><input name="self_email" type="checkbox" /> <span class="slf_mail_txt">Please, check if you would like to get a copy of this email.</span></div>
</div>
</div>
<div class="form_row">
<div class="form-group"><label for="form_message">Message *
<span id="frm_msg" class="msg-error"></span>
<textarea id="form_message" class="form-control qc_msg" name="message" required="true" rows="4" pattern="/^[a-zA-Z0-9 \(\)\n]*$/" data-error="Please,leave us a message."></textarea></label></div>
</div>
<div class="form_row"><span id="cerror" class="msg-error error"></span>
<div id="recaptcha" class="g-recaptcha" data-sitekey="6Ld3ZrAUAAAAAH1nGKCOZgGq-ECOCgZRVMob5Vnm"></div>
</div>
<div class="form_row captcha_gap"><button id="btn-validate" class="baton contact_button" onclick="return callValidation();">Send Your Query</button></div>
</form></div>
</div>
</div>