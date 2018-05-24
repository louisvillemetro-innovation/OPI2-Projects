---
title: Contact
layout: full-page
lede_markdown: To get in touch about specific projects or if you’re a City department
  interested in collaborating with us, please contact [oci@louisvilleky.gov](mailto:oci@louisvilleky.gov).
secondary_lede_markdown:
---

<form id="GD-snippet-form" action="https://public.govdelivery.com/accounts/KYLOUISVILLE/subscribers/qualify" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="Xzm9plCmbwSDFa/dSLMn/ayng8i7EadTIStnH/klwFccfsqJwJG38kaXBfYL6o0u/ldrWQbK6pUrXJLJy0G0ew==" />
<input type="hidden" name="topic_id" id="topic_id" value="KYLOUISVILLE_618" />
<fieldset>
<legend>
Subscribe / Manage Preferences / Unsubscribe
</legend>
<div>
<p><span style="font-size: small;"><strong>Enter your email or text below</strong> to s</span><span style="font-size: small;">ubscribe to a wide range of e-news topics from Metro Government, a</span><span style="font-size: small;">ccess your subscriber preferences or u</span><span style="font-size: small;">nsubscribe:</span></p>
</div>
<ol class='form'>
<li>
<label for="subscription_type">Email or Text:</label>
<div class='input_group'>
<select name="subscription_type" id="subscription_type"><option selected="selected" value="email">Email</option>
<option value="phone">SMS/Text Message</option></select>
</div>

</li>
<li class='wireless_fields' style='display: none'>
<label for="phone"><img class="required" src="https://public.govdelivery.com/static/required.gif" alt="Required" />Wireless Number</label>
<div class='input_group'>
<select name="country_code_display" id="country_code_display" disabled="disabled" aria-label="Country code"><option value="1 (US)">1 (US)</option>
<option value="1">1</option></select>
<input type="hidden" name="country_code" id="country_code" value="1" title="Country code" />

<input type="text" name="phone" id="phone" class="medium" title="Wireless Number" />
</div>

</li>
<li class='email_fields' style='display: block'>
<label for="email"><img class="required" src="https://public.govdelivery.com/static/required.gif" alt="Required" />Email Address</label>
<input type="text" name="email" id="email" class="long" />

</li>
</ol>
<div class='button_panel'>
<input type="submit" name="commit" value="Submit" class="form_button" />
</div>
</fieldset>
</form>

<script type='text/javascript'>
  //<![CDATA[
    var GOVDSNIPPET = function() {
      var form  = document.getElementById('GD-snippet-form');
      var typeSelect = form.getElementsByTagName('select')[0];
      var getStyleType = function(type) {
        return typeSelect.value === type ? 'block' : 'none';
      };
      var toggleType = function() {
        form.getElementsByTagName('li')[2].style.display = getStyleType('email');
        form.getElementsByTagName('li')[1].style.display = getStyleType('phone');
      };
      if (typeSelect.addEventListener) {
        typeSelect.addEventListener('change', toggleType);
      } else if (typeSelect.attachEvent)  {
        typeSelect.attachEvent('onchange', toggleType);
      }
    }();
  //]]>
</script>
