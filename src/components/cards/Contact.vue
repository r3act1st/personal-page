<template>
  <div class="card-inner contacts" id="contacts-card">
    <div class="card-wrap" style="">
      <div class="content contacts">
        <div class="title"><span class="first-word">Get</span> in Touch</div>

        <div class="row">
          <div class="col col-d-12 col-t-12 col-m-12 border-line-v">
            <div class="info-list">
              <ul>
                <li><strong>Address . . . . .</strong> Warszawa, Poland</li>
                <li><strong>Email . . . . .</strong>bogdanywork@gmail.com</li>
                <li><strong>Phone . . . . .</strong> (+48) 791380215</li>
                <li><strong>Freelance . . . . .</strong> Available</li>
              </ul>
            </div>
          </div>
          <div class="clear"></div>
        </div>
      </div>

      <!--
						Contact Form
					-->
      <div class="content contacts">
        <!-- title -->
        <div class="title"><span class="first-word">Contact</span> Form</div>

        <!-- content -->
        <div class="row">
          <div class="col col-d-12 col-t-12 col-m-12 border-line-v">
            <div class="contact_form">
              <form id="cform" method="post" novalidate="novalidate">
                <div class="row">
                  <div class="col col-d-6 col-t-6 col-m-12">
                    <div class="group-val">
                      <input type="text" name="name" placeholder="Full Name" />
                    </div>
                  </div>
                  <div class="col col-d-6 col-t-6 col-m-12">
                    <div class="group-val">
                      <input
                        type="text"
                        name="email"
                        placeholder="Email Address"
                      />
                    </div>
                  </div>
                  <div class="col col-d-12 col-t-12 col-m-12">
                    <div class="group-val">
                      <textarea
                        name="message"
                        placeholder="Your Message"
                      ></textarea>
                    </div>
                  </div>
                </div>
                <div class="align-left">
                  <a
                    href="#"
                    class="button"
                    onclick="$('#cform').submit(); return false;"
                  >
                    <span class="text">Send Message</span>
                    <span class="arrow"></span>
                  </a>
                </div>
              </form>
              <div class="alert-success">
                <p>Thanks, your message is sent successfully.</p>
              </div>
            </div>
          </div>
          <div class="clear"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Contact",
  components: {},
};
</script>
