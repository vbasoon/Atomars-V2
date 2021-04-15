<template>
<div>
  <section class="section1">
         <div class="nav-bread"><p>Fiat and Spot > Deposit</p></div>
         <div class="nav1"><span class="tab1"><a>Deposit</a></span><span class="tab2"><a>Withdraw</a></span></div>
         <div class="nav2">
            <div class="left-nav"><span>Crypto</span><span>Fiat</span></div>
            <div class="right-nav">Need Help? <span><img src="/images/help.png" alt=""></span></div>
             </div>
         <div class="context">
          
          <h4>1. Select currency and payment method</h4>
          <div class="select-currency">
             <label class="label" for="currency">Currency</label><br>
             <select class="select-style" name="" id="currency">
                <option>USD</option>
                <option>EUR</option>
                <option>BTC</option>
             </select>
         </div>
         <div class="recomended">
            <div class="subtitle">
               <h4>Recomended</h4><span class="hot"><img src="/images/hot_label.png" alt=""></span>
            </div>
            <div class="card card1">
               <span class="card-icon">
                  <span><img src="/images/change_icon.png" alt=""></span>
               </span>
               <div class="card-desc">
                  <p>Silvergate Bank (SWIFT)</p>
                  <span>+ 30 USD Fee</span>
               </div>
               </div>
            <div class="card card2">
               <span class="card-icon">
                  <span><img src="/images/change_icon.png" alt=""></span>
               </span>
               <div class="card-desc">
                  <p>Silvergate Bank (SEN)</p>
                  <span>+ 0 USDT Fee</span>
               </div>

            </div>
         </div>
         </div>
      
      </section>
      
      <section class="section2">
          
         <div class="context">
            
         <div class="details">
               <h4 class="details__title">2. Payment details</h4>
               <div class="info-block alert">
                  <span class="atention"><img src="/images/atention.png" alt=""></span><p> For this payment method, USD is automatically stored as BUSD in a 1:1 ratio</p>
               </div>
         </div>
         <div class="ammount">
            <h3 class="ammount__title">Enter Amount</h3>
            <label class="label" for="ammount">Ammount</label>
            <input class="input-ammount"type="text" id="ammount" placeholder="USD">
            <div class="result">
               <p><span>Fee:  </span>     0.00USD</p>
               <p><span>You will get:     </span>  0.00BUSD</p>
            </div>
            <div class="notes">
               <div class="notes__title"><h3 class="notes__title-text">Important notes</h3> 
               </div>
               <div class="notes__title-desc">
            <p>- You can find your deposited amount in your Crypto Balance.</p>
            <p>- Your BUSD can be withdrawn as USD！</p>
            <p>- Bank transfer fees depend on the bank you use.</p>
            <p>- The arrival time of your deposit depends on the region of your sending bank. 
            Usually it takes 2-4 business days.</p>  
               </div>
            </div>
            <div class="section2__button"><a href="#">Continue</a></div>
               
         </div>
            
         </div>
         
      </section>
  
      </div>
</template>

<script>
export default {}
</script>

<style>
section {
  color: black;
  padding: 20px;
  background-color: white;
}

.nav-bread {
  font-size: 14px;
  margin-bottom: 20px;
  color: #788290;
}

.nav1 {
  padding-bottom: 30px;
  color: black;
}

.tab1 a,
.tab2 a {
  font-size: 22px;
  color: black;
  text-decoration: none;
  padding-bottom: 15px;
  border-bottom: 2px solid transparent;
  transition: all 0.2s ease-in-out;
}

.tab1 a:hover,
.tab2 a:hover {
  transform: scale(1.3);
  border-bottom: 2px solid rgba(0, 87, 255, 1);
  cursor: pointer;
}

.nav2 {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 16px;
}

.left-nav {
  font-size: 16px;
  padding: 8px;
  transition: all 0.2s ease-in-out;
}

.left-nav span {
  margin-right: 10px;
  color: rgba(120, 130, 144, 1);
}

.left-nav span:hover {
  margin-right: 10px;
  color: #000;
  cursor: pointer;
  border-bottom: 2px solid rgba(0, 87, 255, 1);
}

.right-nav {
  display: flex;
  font-size: 14px;
}

.select-style {
  display: block;
  padding: 10px;
  width: 100%;
  border: none;
  background-color: white;
  border-bottom: 0.2px solid #c5c5c5;
}

.label {
  font-size: 14px;
}

.subtitle {
  display: flex;
}

.hot {
  margin-left: 10px;
}

.recomended {
  padding-top: 20px;
}

.card {
  display: flex;
  position: relative;
  border-radius: 5px;
  margin-bottom: 20px;
}

.card1::before {
  content: '';
  display: block;
  position: absolute;
  top: -16px;
  right: -17px;
  width: 50px;
  height: 50px;
  background-image: url('/images/poligon.png');
  background-size: 50px 50px;
  background-repeat: no-repeat;
  background-position: right;
}

.card1::after {
  content: '';
  display: block;
  position: absolute;
  top: 3px;
  right: -36px;
  width: 50px;
  height: 50px;
  background-image: url('/images/Vector.png');
  background-size: 10px 10px;
  background-repeat: no-repeat;
}

.card1 {
  margin-top: 20px;
  border: 1px solid rgba(0, 87, 255, 1);
}

.card2 {
  border: 0.5px solid #c5c5c5;
}

.card-icon {
  padding: 20px;
}

.card-desc {
  display: flex;
  width: 100%;
  flex-direction: column;
  justify-content: center;
  padding-left: 20px;
}

.card-desc span {
  font-size: 13px;
  color: rgba(0, 87, 255, 1);
}

.section2 {
  margin-top: 20px;
}

.details__title {
  padding: 20px 0;
}

.info-block {
  display: flex;
  align-items: center;
  font-size: 14px;
  background-color: rgba(0, 87, 255, 0.3);
  padding: 10px;
  border-radius: 3px;
  margin-bottom: 30px;
}

.atention {
  margin-right: 10px;
}

.ammount__title {
  margin-bottom: 20px;
}

.input-ammount {
  display: block;
  padding: 10px;
  width: 100%;
  border: none;
  background-color: white;
  border-bottom: 0.2px solid #c5c5c5;
  margin-bottom: 20px;
}

.input-ammount[placeholder] {
  text-align: end;
}

.result {
  margin-bottom: 20px;
  color: #1E2329;
}

.result span {
  color: rgba(120, 130, 144, 1);
  margin-right: 10px;
}

.notes_title {
  margin-bottom: 20px;
}

.notes__title-text {
  margin-bottom: 20px;
}

.notes__title-desc {
  margin-bottom: 20px;
}

.section2__button {
  width: 100%;
  background-color: rgba(0, 87, 255, 0.3);
  text-align: center;
  padding: 10px;
  border-radius: 3px;
  margin-bottom: 30px;
}

.section2__button a {
  font-size: 20px;
  color: #1e2329;
}

.section2__button a:hover {
  text-decoration: none;
}
</style>
