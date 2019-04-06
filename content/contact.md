---
date: "2014-04-09"
title: "Contact"
---

<form id="contact-form" method="post" action="contact.php" role="form">

    <div class="messages"></div>

    <div class="controls">

        <div class="row">
            <div class="col-md-6">
                <div class="form-group">
                   
                    <input id="form_name" type="text" name="name" class="form-control" placeholder="First name" required="required" data-error="This is required.">
                    <div class="help-block with-errors"></div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="form-group">
                 
                    <input id="form_lastname" type="text" name="surname" class="form-control" placeholder="Last name" required="required" data-error="This is required.">
                    <div class="help-block with-errors"></div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-6">
                <div class="form-group">
                  
                    <input id="form_email" type="email" name="email" class="form-control" placeholder="Email" required="required" data-error="Valid email required.">
                    <div class="help-block with-errors"></div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-12">
                <div class="form-group">
                
                    <textarea id="form_message" name="message" class="form-control" placeholder="Message" rows="4" required="required" data-error="This is required."></textarea>
                    <div class="help-block with-errors"></div>
                </div>
            </div>
            <div class="col-md-12">
                <input type="submit" class="btn btn-success btn-send" value="Send message">
            </div>
        </div>

    </div>

</form>


