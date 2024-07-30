
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
    <footer class="footer">
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
  height: 100vh; /* Full viewport height */
  display: flex;
  flex-direction: column;
}

.header {
  background-color: #fffefe; /* Light gray background for header */
  padding: 10px 20px; /* Padding around the header */
  display: flex;
  align-items: flex-start; /* Align items to the top */
  justify-content: space-between; /* Space out items horizontally */
  border-bottom: 1px solid #fffefe; /* Bottom border for the header */
}

.logoo {
  align-self: flex-start; /* Align logo to the top left */
  width: 6%; /* Set a fixed width for the logo */
  height: auto;
}

.header-button {
  background-color: #EBC82A; /* Button background color */
  color: rgb(6, 6, 6); /* Button text color */
  border: none; /* Remove default border */
  padding: 10px 20px; /* Button padding */
  border-radius: 5px; /* Slightly rounded corners */
  cursor: pointer; /* Pointer cursor on hover */
  font-size: 16px; /* Font size */
}

.header-button:hover {
  background-color: #e3c86f; /* Darker color on hover */
}

.xxx {
  width: 30%;
  height: 30%;
}

.main-content {
  flex: 1; /* Take up remaining space */
  display: flex;
  padding: 20px; /* Padding around the content */
}

.content-left {
  flex: 1; /* Take up available space */
  display: flex;
  flex-direction: column; /* Stack items vertically */
  justify-content: flex-start; /* Align content to the top */
  align-items: flex-start; /* Align content to the left */
}

.main-text {
  font-size: 36px; /* Font size for the main text */
  color: #080808; /* Text color */
  margin-bottom: 20px; /* Space between text elements */
}

.item-container {
  margin-bottom: 20px; /* Space between items */
}

.item-content {
  display: flex;
  align-items: center; /* Center align items vertically */
}

.item-icon {
  margin-right: 10px; /* Space between image and text */
  width: 40px; /* Adjust width if needed */
  height: 40px; /* Adjust height if needed */
}

.item-text {
  display: flex;
  flex-direction: column; /* Stack title and description vertically */
}

.item-title {
  font-size: 36px; /* Font size for item titles */
  color: #FF9C00; /* Orange color for item titles */
  margin-bottom: 10px; /* Space between title and description */
  display: block; /* Ensures title is on its own line */
  text-align: left;
}

.item-description {
  font-size: 14px; /* Smaller font size for item descriptions */
  color: #000; /* Black color for description text */
  max-width: 500px; /* Set a max-width for better layout */
  line-height: 1.5; /* Line height for readability */
  text-align: left;
}

.button-container {
  display: flex;
  flex-direction: row; /* Stack buttons horizontally */
  justify-content: flex-end; /* Align buttons to the right */
  margin-top: 20px; /* Space above the button container */
}

.download-button {
  background-color: #FBF4D4; /* Button background color */
  color: rgb(6, 6, 6); /* Button text color */
  border: none; /* Remove default border */
  padding: 10px 20px; /* Button padding */
  border-radius: 5px; /* Slightly rounded corners */
  cursor: pointer; /* Pointer cursor on hover */
  font-size: 16px; /* Font size */
  margin-left: 10px; /* Space between buttons */
  width: 40%;
  height: 70%;
}

.download-button:hover {
  background-color: #515252; /* Darker color on hover */
}

.image-container {
  display: flex;
  align-items: flex-start; /* Align items to the top */
  justify-content: flex-end; /* Align items to the right */
  padding-top: 10px; /* Add space above the image */
  margin-left: 20px; /* Add space to the left of the image */
}

.right-image {
  max-width: 500px; /* Adjust the width as needed */
  height: auto; /* Maintain aspect ratio */
}

.footer {
  background-color: #FBF4D4; /* Footer background color */
  padding: 20px; /* Padding around the footer content */
  font-size: 14px; /* Font size for footer text */
}

.footer-top {
  display: flex;
  justify-content: space-between; /* Space out footer sections horizontally */
  align-items: flex-start; /* Align items to the top */
}

.footer-left {
  flex: 1;
  display: flex;
  flex-direction: column;
}

.footer-logo {
  max-width: 100px; /* Adjust logo size */
  height: auto; /* Maintain aspect ratio */
  margin-bottom: 10px; /* Space below the logo */
}

.footer-text {
  font-size: 14px; /* Font size for footer text */
  margin-bottom: 10px; /* Space below text */
}

.footer-center {
  flex: 1;
  display: flex;
  justify-content: center; /* Center align the links */
}

.footer-links-container {
  display: flex;
  justify-content: space-between; /* Space out the link sections horizontally */
  width: 100%; /* Full width */
}

.quick-links, .website-maps {
  display: flex;
  flex-direction: column;
}

.footer-heading {
  font-weight: bold; /* Bold heading */
  margin-bottom: 10px; /* Space below heading */
}

.footer-links {
  list-style-type: disc; /* Remove default list styling */
  padding: 0; /* Remove default padding */
  margin: 0; /* Remove default margin */
  padding-left: 20px;
}

.footer-links li {
  margin-bottom: 5px; /* Space between links */
  color: #111312; /* Link color */
}
.footer-links li::marker {
  color: #4DA747; /* Bullet point color */
}

.footer-right {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: flex-end; /* Align items to the right */
}

.footer-contact-item {
  display: flex;
  flex-direction: column;
  align-items: flex-end; /* Align items to the right */
}

.contact-item {
  display: flex;
  align-items: center; /* Center align icon and text */
  margin-bottom: 5px; /* Space between contact items */
}

.contact-icon {
  margin-right: 10px; /* Space between icon and text */
  width: 20px; /* Adjust width if needed */
  height: 20px; /* Adjust height if needed */
}
.footer-bottom {
  display: flex;
  justify-content: space-between; /* Space out footer bottom elements */
  align-items: center; /* Center align items vertically */
  margin-top: 20px; /* Space above footer bottom */
  padding: 0 10px;
  position: relative; /* Ensure the positioning context for the vector image */
}

.group-icon {
  width: 20%; /* Adjust width as needed */
  height: auto; /* Maintain aspect ratio */
  margin: 0 auto; /* Center horizontally */
}

.vector {
  width: 500px; /* Adjust width as needed */
  height: auto; /* Maintain aspect ratio */
  position: absolute; /* Position it absolutely within the footer */
  right: 0; /* Align to the right edge */
  bottom: 0; /* Align to the bottom edge */
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

</style>



