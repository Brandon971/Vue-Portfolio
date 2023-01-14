<template >
  
  <div class="container contact-form">
            <div class="contact-image">
                <img src="https://image.ibb.co/kUagtU/rocket_contact.png" alt="rocket_contact"/>
            </div>
            <form action="https://formspree.io/f/mrgdowaq" method="post" target="_blank">
                <h3>Contact Me</h3>
               <div class="row">
                    <div class="col-md-6">
                        <div class="form-group">
                            <input type="text" name="txtName" class="form-control" required="required" data-error="message is required" placeholder="Your Name *" value="" />
                        </div>
                        <div class="form-group">
                            <input type="text" name="txtEmail" class="form-control" required="required" data-error="message is required" placeholder="Your Email *" value="" />
                        </div>
                        <div class="form-group">
                            <input type="number" name="txtPhone" class="form-control" required="required" data-error="message is required" placeholder="Your Phone Number *" value="" />
                        </div>
                        <div class="form-group">
                            <input type="submit" name="btnSubmit" class="btnContact" value="Send Message" />
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="form-group">
                            <textarea name="txtMsg" class="form-control" required="required" data-error="message is required" placeholder="Your Message *" style="width: 100%; height: 150px;"></textarea>
                            <li class="list-inline-item">
                              <a href="https://www.linkedin.com/company/linkedin/" target="_blank"><i class="fab fa-linkedin-in"></i></a>
                          </li>
                          <li class="list-inline-item">
                             <a href="https://www.instagram.com/_brandonswinton_/" target="_blank"><i class="fab fa-instagram"></i></a>
                          </li>
                        </div>
                    </div>
                </div>
            </form>
</div>
</template>
<script>
export default {

}
</script>
<style>

.contact-form{
  border-radius: 10px;
  margin-top: 3%;
    background: #fff;
    width: 70%;
}
.contact-form .form-control{
    border-radius:1rem;
}
.contact-image{
    text-align: center;
}
.contact-image img{
    border-radius: 6rem;
    width: 11%;
    margin-top: -3%;
    transform: rotate(29deg);
}
.contact-form form{
    padding: 14%;
}
.contact-form form .row{
    margin-bottom: -7%;
}
.contact-form h3{
    margin-bottom: 8%;
    margin-top: -10%;
    text-align: center;
    color: lightslategray;
}
.contact-form .btnContact {
    width: 50%;
    border: none;
    border-radius: 1rem;
    padding: 1.5%;
    background: #b82227;
    font-weight: 600;
    color: #fff;
    cursor: pointer;
}
.btnContactSubmit
{
    width: 50%;
    border-radius: 1rem;
    padding: 1.5%;
    color: #fff;
    background-color: #0062cc;
    border: none;
    cursor: pointer;
}
.list-inline-item{
    margin-left: 30%;
}
@media screen and (max-width:720px){

}
  
</style>