# PHP for contact form submission

## Built With php

### Getting Started

First we download php file and add to your file directory. Create a database and import this table contact.

#### Prerequisites

Used php version : 7.0

Used db version : Apache/2.4.41 (Unix) OpenSSL/1.1.1c PHP/7.3.9 mod_perl/2.0.8-dev Perl/v5.16.3

#### HTML form model

      <form class="register-form" action="contact.php " method="post">
            <div class="form-group">
                <label for="name"><i class="zmdi zmdi-account material-icons-name"></i></label>
                <input type="text" name="name" id="name" placeholder="Your Name" required/>
            </div>
            <div class="form-group">
                <label for="class"><i class="fa fa-graduation-cap"></i></label>
                <input type="class" name="class" id="class" placeholder="Standard" required/>
            </div>
            <div class="form-group">
                <label for="email"><i class="zmdi zmdi-email"></i></label>
                <input type="email" name="email" id="email" placeholder="Your Email" required/>
            </div>
            <div class="form-group">
                <label for="mobile"><i class="fa fa-mobile" style="font-size: 20px;"></i></label>
                <input type="number" name="mobile" id="mobile" placeholder="Mobile number" required/>
            </div>
            <div class="form-group">
                <label for="mobile"><i class="fa fa-whatsapp" style="font-size: 16spx;"></i></label>
                <input type="number" name="wmobile" id="wmobile" placeholder="Whatsapp number" required/>
            </div>
            <div class="form-group">
                <label for="message"><i class="fa fa-comment" style="font-size: 16spx;"></i></label>
                <input type="message" name="message" id="message" placeholder="Give a message" required/>
            </div>
            <div class="form-group form-button">
                <input type="submit" name="submit" class="form-submit" />
            </div>
        </form>
