<template>
  <footer>
         
         <div class="footer-menu">
                     
            <div class="footer-menu__item about"><p class="footer-menu__point">About</p><span class="footer-menu__span">+</span></div>
         
            <div class="footer-menu__item product"><p class="footer-menu__point">Product</p><span class="footer-menu__span">+</span></div>
         
            <div class="footer-menu__item services"><p class="footer-menu__point">Sevices</p><span class="footer-menu__span">+</span></div>
         
            <div class="footer-menu__item help"><p class="footer-menu__point">Help</p><span class="footer-menu__span">+</span></div>
         
            <div class="contact-us"><p class="footer-menu__point contact-us__title">Contact Us</p>
               <p class="email">Email us: <a>email@gmail.com</a></p>
               <p class="email">Business: <a>email@gmail.com</a></p>
     
            </div> 
               <div class="social">
                  <div class="social-icons">
                     <span class="social-icon"><img src="/images/telegram_icon.png" alt=""></span>
                     <span class="social-icon"><img src="/images/instagram_icon.png" alt=""></span>
                     <span class="social-icon"><img src="/images/telegram_icon.png" alt=""></span>
                     <span class="social-icon"><img src="/images/twitter.png" alt=""></span>
                     <span class="social-icon"><img src="/images/email.png" alt=""></span>
                  </div>
                  <div class="select-eng">
                     <select class="select-lang" name="lang" id="lang">
                        <option>English</option>
                        <option>German</option>
                        <option>Italian</option>
                     </select>
                  </div>
               </div>
            
             
         </div>
        
         <div class="copyright"><p class="copyright-text">© 2013-2021 Gate Technology Incorporated. All Rights Reserved.</p></div>
      </footer>
</template>

<script>
export default {

}
</script>

<style>
footer {
  padding: 20px;
}

.footer-menu {
  margin-top: 80px;
}

.footer-menu__item {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}

.footer-menu__point {
  font-size: 18px;
  font-weight: 500;
}

.footer-menu__point:last-child {
  margin-bottom: 20px;
}

.contact_us {
  display: block;
  margin-top: 0;
  margin-bottom: 20px;
}

.contact-us__title{
  font-size: 18px;
  font-weight: 500;
  margin-bottom: 10px;
}

p.email {
  font-size: 12px;
  font-weight: 500;
  margin-bottom: 10px;
}

p.email a{
  color: rgba(120, 130, 144, 1);
}

.social {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}

.social-icons {
  display: flex;
  width: 250px;
  justify-content: space-between;
  align-items: center;
}

.select-lang {
  background-color: #fff;
  border-radius: 20px;
  padding: 10px;
  margin-right: 20px;
  font-size: 14px;
}

.select-lang:active {
  border: 0;
}

.copyright-text {
  text-align: center;
  font-size: 10px;
}
</style>