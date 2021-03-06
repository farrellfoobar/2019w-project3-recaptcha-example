## CS 122B Project 3 reCAPTCHA example

This example shows how to add reCAPTCHA to your frontend and backend.

### To run this example: 
1. clone this repository using `git clone https://github.com/UCI-Chenli-teaching/2019w-project3-recaptcha-example.git`
2. open Eclipse -> File -> import -> under "Maven" -> "Existing Maven Projects" -> Click "Next".
3. For "Root Directory", click "Browse" and select this repository's folder. Click "Finish".
4. If you haven't done so, get a [reCAPTCHA](https://www.google.com/recaptcha/intro/v3.html) from Google. 
   `Admin Console` -> `Register a new site` -> Choose `reCAPTCHA v2` -> Enter both your AWS public IP and "localhost" -> Click "Submit"
5. In `src/RecaptchaConstants.java`, replace `YOUR_SECRET_KEY;` with your own reCAPTCHA `secret key`.
6. In `WebContent/index.html`, replace `data-sitekey="YOUR_SITE_KEY"` with your own reCAPTCHA `site key`.
7. In `src/FormRecaptcha.java`, change the mysql username and password.
8. You can run this project on Tomcat (both local machine and AWS).
