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
      <dl>
        <dt>Email</dt>
        <dd><a href="mailto:{{ site.email }}">{{ site.email }}</a></dd>
        <dt>Phone</dt>
        <dd>858-534-8321</dd>
    </dl>
</div>

<div class="col-sm-5">

<h4 class="text-left">Address</h4>
{% include widgets/visit-us.html %}
</div>
