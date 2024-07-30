
<template>
  <div class="container">
    <header class="header">
      <img class="logoo" src="../assets/logoo.png" />
      <button class="header-button">Playground Management</button>
    </header>
    <main class="main-content">
      <div class="content-left">
        <span class="main-text">Download Our App</span>
        <div class="item-container">
          <div class="item-content">
            <img class="item-icon" src="../assets/pcs.png" />
            <div class="item-text">
              <span class="item-title">Search</span>
              <span class="item-description">Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae</span>
            </div>
          </div>
        </div>
        <div class="item-container">
          <div class="item-content">
            <img class="item-icon" src="../assets/shm.png" />
            <div class="item-text">
              <span class="item-title">Choose</span>
              <span class="item-description">Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae</span>
            </div>
          </div>
        </div>
        <div class="item-container">
          <div class="item-content">
            <img class="item-icon" src="../assets/mgld.png" />
            <div class="item-text">
              <span class="item-title">Fill Your Date</span>
              <span class="item-description">Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae</span>
            </div>
          </div>
        </div>
        <div class="item-container">
          <div class="item-content">
            <img class="item-icon" src="../assets/yd.png" />
            <div class="item-text">
              <span class="item-title">Pay</span>
              <span class="item-description">Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae</span>
            </div>
          </div>
        </div>
        <div class="button-container">
          <button class="download-button">
            <img class="buttonapple" src="../assets/apple.png" />Download Now
          </button>
          <button class="download-button">
            <img class="buttonmoth" src="../assets/moth.png" />Download Now
          </button>
          <button class="download-button">
            <img class="buttonmorba" src="../assets/morba.png" />Download Now
          </button>
        </div>
      </div>
      <div class="image-container">
        <img class="right-image" src="../assets/gwal.png" />
      </div>
    </main>
    <footer class="footer" >
      <div class="footer-top">
        <div class="footer-left">
          <img class="footer-logo" src="../assets/logoo.png" />
          <span class="footer-text">Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur ma</span>
          <p><strong>Commercial register:</strong> 244644757555</p>
          <p><strong>VAT number:</strong> 244644757555</p>
        </div>
        <div class="footer-center">
          <div class="footer-links-container">
            <div class="quick-links">
              <span class="footer-heading">Quick Links</span>
              <ul class="footer-links">
                <li>Download App</li>
                <li>Prices</li>
              </ul>
            </div>
            <div class="website-maps">
              <span class="footer-heading">Website Maps</span>
              <ul class="footer-links">
                <li>Return Policy</li>
                <li>Service Agreement</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="footer-right">
          <div class="footer-contact-item">
            <span class="footer-heading">Contact Information</span>
            <div class="contact-item">
              <img class="contact-icon" src="../assets/call.png" /> +966424225255
            </div>
            <div class="contact-item">
              <img class="contact-icon" src="../assets/sms.png" /> care@ngliat.com
            </div>
            <img class="xxx" src="../assets/xxx.png" />
          </div>
        </div>
      </div>
      <div class="footer-bottom">
        <p>Copyright fo ngliat 2023</p>
        <img class="group-icon" src="../assets/Group.png" />
        <img class="vector" src="../assets/Vector.png" />
      </div>
    </footer>
  </div>
</template>

<style scoped>
.container {
  background-color: white;
  height: 100vh; 
  display: flex;
  flex-direction: column;
}

.header {
  background-color: #fffefe; 
  padding: 10px 20px; 
  display: flex;
  align-items: flex-start; 
  justify-content: space-between; 
  border-bottom: 1px solid #fffefe; 
}

.logoo {
  align-self: flex-start; 
  width: 6%; 
  height: auto;
}

.header-button {
  background-color: #EBC82A; 
  color: rgb(6, 6, 6); 
  border: none; 
  padding: 10px 20px; 
  border-radius: 5px; 
  cursor: pointer; 
  font-size: 16px; 
}

.header-button:hover {
  background-color: #e3c86f; 
}

.xxx {
  width: 30%;
  height: 30%;
}

.main-content {
  flex: 1; 
  display: flex;
  padding: 20px;
}

.content-left {
  flex: 1;
  display: flex;
  flex-direction: column; 
  justify-content: flex-start; 
  align-items: flex-start; 
}

.main-text {
  font-size: 36px; 
  color: #080808; 
  margin-bottom: 20px; 
}

.item-container {
  margin-bottom: 20px; 
}

.item-content {
  display: flex;
  align-items: center; 
}

.item-icon {
  margin-right: 10px; 
  width: 40px; 
  height: 40px; 
}

.item-text {
  display: flex;
  flex-direction: column; 
}

.item-title {
  font-size: 36px; 
  color: #FF9C00; 
  margin-bottom: 10px; 
  display: block; 
  text-align: left;
}

.item-description {
  font-size: 14px; 
  color: #000; 
  max-width: 500px; 
  line-height: 1.5; 
  text-align: left;
}

.button-container {
  display: flex;
  flex-direction: row; 
  justify-content: flex-end; 
  margin-top: 20px; 
}

.download-button {
  background-color: #FBF4D4; 
  color: rgb(6, 6, 6); 
  border: none; 
  padding: 10px 10px; 
  border-radius: 5px; 
  cursor: pointer; 
  font-size: 14px; 
  margin-left: 10px; 
  width: 180px;
  height: 50px;
  margin: 5px;
}

.download-button:hover {
  background-color: #515252; 
}

.image-container {
  display: flex;
  align-items: flex-start; 
  justify-content: flex-end; 
  padding-top: 10px;
  margin-left: 20px; 
  width: 50%;
}

.right-image {
  max-width: 500px; 
  height: auto; 
}

.footer {
  background-color: #FBF4D4; 
  padding: 20px; 
  font-size: 12px; 
}

.footer-top {
  display: flex;
  justify-content: space-between; 
  align-items: flex-start; 
}

.footer-left {
  flex: 1;
  display: flex;
  flex-direction: column;
  text-align: left;
}

.footer-logo {
  max-width: 80px; 
  height: auto; 
  margin-bottom: 10px; 
}

.footer-text {
  font-size: 14px; 
  margin-bottom: 10px; 
  text-align: left;
  width: 66%;
}

.footer-center {
  flex: 1;
  display: flex;
  justify-content: center; 
}

.footer-links-container {
  display: flex;
  justify-content: space-between; 
  width: 100%; 
}

.quick-links, .website-maps {
  display: flex;
  flex-direction: column;
}

.footer-heading {
  font-weight: bold; 
  margin-bottom: 10px; 
}

.footer-links {
  list-style-type: disc; 
  padding: 0; 
  margin: 0; 
  padding-left: 20px;
}

.footer-links li {
  margin-bottom: 5px; 
  color: #111312;
}
.footer-links li::marker {
  color: #4DA747; 
}

.footer-right {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: flex-end; 
}

.footer-contact-item {
  display: flex;
  flex-direction: column;
  align-items: flex-end; 
}

.contact-item {
  display: flex;
  align-items: center; 
  margin-bottom: 5px; 
}

.contact-icon {
  margin-right: 10px; 
  width: 20px; 
  height: 20px; 
}
.footer-bottom {
  display: flex;
  justify-content: space-between; 
  align-items: center; 
  
  padding: 0 ;
  position: relative; 
}

.group-icon {
  width: 20%; 
  height: auto; 
  margin: 0 auto; 
}

.vector {
  width: 40%;

  height: 50%; 
 margin-left: auto;
}
.buttonapple{
  width: 20%;
  height: 50%;
}
.buttonmoth{
  width: 20%;
  height: 50%;
}
.buttonmorba{
  width: 20%;
  height: 50%;
}
@media (max-width: 768px) {
  .container {
    flex-direction: column; 
  }
  
  .header {
    flex-direction: column; 
    align-items: center; 
  }
  
  .header-button {
    margin-top: 10px; 
  }
  
  .main-content {
    flex-direction: column-reverse; 
    align-items: center; 
  }
  
  .content-left {
    width: 100%; 
    padding: 10px; 
  }
  
  
  .footer-top {
    flex-direction: column; 
    align-items: center; 
  }
  
  .footer-left, .footer-center, .footer-right {
    width: 100%; 
    margin-bottom: 10px; 
  }
  
  .footer-links-container {
    flex-direction: column; 
  }
  .button-container{
    width: 80%;
    margin-top: 10px;
    font-size: 12px;
  }
  .image-container{
    width: 50%;
    margin-top: 20px;
    justify-content: center;
  }
}
</style>



