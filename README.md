[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/f6dTnkNL)

<h1>MILESTONE 1 - WEEK 5 ASSIGNMENT</h1>


<div>
<h2>Table of Contents</h2>
<ol>
<li>HTML Structure</li><ul>
<li>index.html</li>
<li>form.html</li>
</ul>
<li>Readme File</li>
<li>Assets</li>
<ul>
    <li>Style CSS</li>
    <li>Fonts</li>
    <li>Image</li>
    <li>Javascript</li></ul>

</div>

### ---

<div>
<h2>Responsive Mode</h2>

#### Dekstop Mode
Dekstop mode use Dimension value from <b>1024 px and up</b>

<img src="assets/img/web.png">



Dekstop result of generate a lighthouse report : 

<img src="/assets/img/dekstop_lighthouse.png">

</div>

#### Tablet Mode
Mobile mode use Dimension from Samsung Galaxy with size resposivity in <b>max-width 1024px</b>.
<img src="assets/img/mobile.png">

Mobile result of generate a lighthouse report : 

<img src="/assets/img/mobile_lighthouse.png">

</div>

#### Mobile Mode
Mobile mode use Dimension from Samsung Galaxy with size resposivity in <b>max-width: 780px</b>.
<img src="assets/img/mobile.png">

Mobile result of generate a lighthouse report : 

<img src="/assets/img/mobile_lighthouse.png">

</div>

### ---

<h2>Deployment</H2>

**Netlify Sign up process & connect Netlify to your Github project.**

- *Register Netlify with Github*

    <img style="padding-bottom: 2%; padding-top: 3%;" width="100%" src="./assets/img/Register netlify.png" alt="Register Netlify">

    1. Open [Netlify.com](https://app.netlify.com/)

    2. Register first, If you don't have an account, you can choose one of several types of entry access. 

    3. This time I will register using the email that is registered as a GitHub account, so I chose log in.

    4. You can also choose to register directly using the GitHub option.

    <br>

    <p align="center"><img style="padding-bottom: 2%; padding-top: 2%;" width="80%" src="./assets/img/login netlify.png" alt="Login Netlify"></p>

    5. Netlify can now be accessed.
    
<br>

**Auto Deployment on Github with Netlify.**

<img style="padding-bottom: 2%; padding-top: 2%;" width="100%" src="./assets/img/deploy with github1.png" alt="deploy with netlify via github1">

5. Login to Netlify has been successful, 

6. To deploy a new project select <b>site</b>, than <b>add new site</b>, and select <b>import an existing project</b>.

7. Select <b>Deploy with Github</b>

8. Go to the repository selection you want to connect.

<img style="padding-bottom: 2%; padding-top: 2%;" width="100%" src="./assets/img/deploy with github2.png" alt="deploy with netlify via github2">

9. Select <b>account Github name to accses</b>

10. Select <b>main folder repository</b>

11. fill in some of the required ones, then select <b>Deploy folder repository</b> and wait for the deploy process

12. Accessing the web address deployed using Netlify has been successful.

<p align="center"><img style="padding-bottom: 2%; padding-top: 2%;" width="80%" src="./assets/img/tampilan web via netlify.png" alt="result deploy with netlify with github"></p>

<p align="center"> <a href="https://resonant-cuchufli-f8924d.netlify.app/">(https://resonant-cuchufli-f8924d.netlify.app/)</a></p>

```css

```
<br>

**How to Connect Your Custom Domain and Domain Name System (Used Subdomain to Connect DNS).**
 
- *<u>Domain Name Sytem Settings</u>*

    We chose Cloudflare as the intermediary connecting Netlify to the custom domain service that has been purchased, and here are the steps :

    1. <p><img style="padding-bottom: 2%; padding-top: 3%;" width="100%" src="./assets/img/cloudflare register.png" alt="Register cloudflare">Open [Cloudflare.com](https://cloudflare.com/). Register first, If you don't have an account, you can register first. This time I already had a registered account, so I choose sign in with google account.</p>

    2. Cloudflare services can now be accessed. The initial display can now be seen, then select "<b>add a website or application</b>"

    3. The initial display can now be seen, then Register your custom domain name and select "<b>continue</b>"

    4. Choose a service that suits your website needs and select <b>continue</b>.

    <br>





    5. <p><img style="padding-bottom: 2%; padding-top: 3%;" width="100%" src="./assets/img/connect cloudflare.png" alt="connected cloudflare in niagahoster">The initial display can now be seen, then Register your custom domain name and select "<b>continue</b>".</p>

    6. The initial display can now be seen, then Register your custom domain name and select "<b>continue</b>"

    7. Open your custom domain service, select the <b>domain</b> menu, then select <b>ringkasan domain</b>. Look for the <b>nameservers</b> menu, then select <b>ubah</b>

    8. The initial display can now be seen, then choose "<b>ganti nama server</b>" in the "<b>pilih nameaserver</b>" menu.

        <br>

    9. <p>  <img style="padding-bottom: 2%; padding-top: 3%;" width="100%" src="./assets/img/copy dns cloudflare ke niagahoster.png" alt="copy dns cloudflare ke niagahoster">Copy Cloudflare nameserver.</p>

    10. Paste Cloudflare nameserver to nameserver your custom domain and select "<b>simpan</b>".

    11. <p><img style="padding-bottom: 2%; padding-top: 3%;" width="100%" src="./assets/img/connect subdomain1.png" alt="connect netlify via cloudflare"> Open and sign in your account in netlify. Select "<b>site overview</b>" and copy url netlify subdomain (<i> example : resonant-cuchufli-f8924d.netlify.app </i>). </p>

    12. Open and sign in your account in cloudflare. Select "<b>DNS -> Records</b>". Select "<b>Add Records</b>" and and complete some of the contents, among others:
    <b>Type = CNAME ; Name (Required) = milestone1 ; Target (Required) = paste url netlify subdomain (*example : resonant-cuchufli-f8924d.netlify.app*) </b> and select "<b>save</b>".

    13. Wait for domain name system access until it is approved.

    <img style="padding-bottom: 2%; padding-top: 3%;" width="100%" src="./assets/img/netlify manage domain1.png" alt="copy dns cloudflare ke niagahoster">

    14. Enter the custom domain name that has been purchased to register on Netlify. Select "<b>*verify*</b>".

    15. Check production domain status.

    <img style="padding-bottom: 2%; padding-top: 3%;" width="100%" src="./assets/img/connect netlify with cloudflare2.png" alt="connect netlify with cloudflare2">

    16. Domain production awaits verification.

    17. Domain production has been verified and is ready to be published.

<br>

**Result custom domain with DNS**

|       Tool     | Tool Website | My Link Website with Custom Domain |
|----------------|--------------|------------------------------------|
|<img width="55%" src="https://media.licdn.com/dms/image/D5612AQF8j904pu6YuA/article-cover_image-shrink_423_752/0/1670684263820?e=1704931200&v=beta&t=7JWbxr3EKDb-lxA4prXJSM_sB5PQTk_BGPA9aUvdnS8"> <img width="70%" src="https://images.glints.com/unsafe/glints-dashboard.s3.amazonaws.com/company-banner-pic/e20dc79c6f6b04c5c61eab31047d504e.jpg">|[Hostinger](https://www.hostinger.co.id/?ppc_campaign=google_search_brand&bidkw=hostinger&gad_source=1&gclid=Cj0KCQiAgK2qBhCHARIsAGACuzk6f_GvQqM5gqiMsgmKCXRqDi5y9D5qAyIVqs6x6oPjx6wU7Lz_FaQaAp_cEALw_wcB) [Niagahoster](https://hpanel.hostinger.com/)|[www.milestone1.imanmaris.tech](https://www.milestone1.imanmaris.tech/) & [milestone1.imanmaris.tech](https://milestone1.imanmaris.tech/)|




<br>




<br>


<h4 align="center"><img width="55%" src="https://e7.pngegg.com/pngimages/348/63/png-clipart-under-construction-under-construction-thumbnail.png"></h4>


---


<p align="center">last created on November 15, 2023</p>
<p align="center"><i>copyright &copy; 2023</i></p>