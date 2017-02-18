---
location: homepage
head:
  title: null
  subtitle: null
style:
  id: contact
  class: 'dark'
  media:
    img:
      url_path: null
      pattern:
      parallax:
      overlay:
      blur: false
  tint_color: 'rgba(163,166,152,0.6)'
cta:
  headline: null
  btnText: null
  btnType: null
  btnLink: null
  subtext: null

---

<div class="col-sm-7">
<h4 class="text-left">Connect</h4>
{% include social-links.html %}
    <h4 class="text-left">Contact Us</h4>
  <span>
    <strong>Email</strong>
    <br>
    <a href="mailto:{{ site.email }}">{{ site.email }}</a>
  </span>
  <span>
    <strong>Phone</strong>
    <br>
858-534-8321
  </span>
</div>

<div class="col-sm-5">

<h4 class="text-left">Address</h4>
{% include widgets/visit-us.html %}
</div>
