---
title: Contact Us
---

<div class="row">
  <div class="column small-12 medium-6">
    <h3>Telephone</h3>
    <p><a href="tel://03-9972-566" class="a--black">(03) 9972 566</a></p>

    <h3>Follow Us</h3>
    {% for social in site.data.social %}
      <p><a href="{{ social.href | prepend: site.baseurl }}" target="_blank" class="a--black">
        <i class="fa fa-15x {{ social.icon }} icon"></i>{{ social.title }}
      </a></p>
    {% endfor %}

    <h3>Opening Hours</h3>
    <table>
      <tbody>
        <tr>
          <td>Sun:</td>
          <td>11:30 AM - 9:30 PM</td>
        </tr>
        <tr>
          <td>Mon:</td>
          <td>11:30 AM - 9:30 PM</td>
        </tr>
        <tr>
          <td>Tue:</td>
          <td>11:30 AM - 9:30 PM</td>
        </tr>
        <tr>
          <td>Wed:</td>
          <td>11:30 AM - 9:30 PM</td>
        </tr>
        <tr>
          <td>Thu:</td>
          <td>11:30 AM - 9:30 PM</td>
        </tr>
        <tr>
          <td>Fri:</td>
          <td>11:30 AM - 9:30 PM</td>
        </tr>
        <tr>
          <td>Sat:</td>
          <td>5:30 PM - 10:00 PM</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="column small-12 medium-6">
    <h3>Location</h3>
    <a href="https://www.google.com.au/maps/dir/''/678+Glen+Huntly+Rd,+Caulfield+South+VIC+3162/" class="a--black" target="_blank"><p>678 Glen Huntly Road <br>
    Caulfield South, 3162 Australia <br></p></a>
    <div class="small-gutter"></div>
    <a href="https://www.google.com.au/maps/dir/''/678+Glen+Huntly+Rd,+Caulfield+South+VIC+3162/" target="_blank">
      <img width="100%" src="http://maps.googleapis.com/maps/api/staticmap?center=6a+Barkly+Ave+Armadale&amp;zoom=16&amp;scale=false&amp;size=640x400&amp;maptype=roadmap&amp;format=png&amp;visual_refresh=true&amp;markers=icon:x%7Cshadow:true%7C6a+Barkly+Ave+Armadale" alt="Google Map of 6a Barkly Ave Armadale&amp;key=AIzaSyBPjcQMI0eNvA_neIB7NZ0xTyUJ4TW2asM">
    </a>
  </div>
</div>
<div class="medium-gutter"></div>

