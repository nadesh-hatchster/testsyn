---
ID: 5344
post_title: Paymil Iframe
author: Olu
post_date: 2015-10-22 17:44:55
post_excerpt: ""
layout: page
permalink: >
  http://www.ecommerce.lotto-social.com/paymil_iframe/
published: true
ulp_version:
  - "4.9"
ulp_onload_mode:
  - default
ulp_onload_period:
  - "5"
ulp_onload_delay:
  - "0"
ulp_onload_close_delay:
  - "0"
ulp_onload_popup:
  - default
ulp_onload_popup_mobile:
  - default
ulp_onexit_mode:
  - default
ulp_onexit_period:
  - "5"
ulp_onexit_popup:
  - default
ulp_onexit_popup_mobile:
  - default
ulp_onscroll_popup:
  - default
ulp_onscroll_popup_mobile:
  - default
ulp_onscroll_mode:
  - default
ulp_onscroll_period:
  - "5"
ulp_onscroll_offset:
  - "600"
ulp_onidle_mode:
  - default
ulp_onidle_delay:
  - "30"
ulp_onidle_period:
  - "5"
ulp_onidle_popup:
  - default
ulp_onidle_popup_mobile:
  - default
slide_template:
  - default
lotto_reg_form:
  - 'no'
---
<?php 
global $PaymillMethod;
echo 'PaymillMethod'.$PaymillMethod ?>
<form action="" method="post" name="IframeCreditCardForm" id="IframeCreditCardForm">	
	<div class="col-lg-12" style="background-color:white; text-align:center;" id='credit-card-formdiv' style='display:none' >
		<div style="display: block;max-width: 300px; display: inline-block;" >
			<h4 id="creditCardText" style='display:none'>Credit Card Details</h4>
			<div> 
				<!-- Other fields of your form -->
				<div id="credit-card-fields">
				<!-- Embedded credit card frame will load here -->
				</div>
				<!-- Other fields of your form -->
			</div>
			<div class="form-group">
				<div class="tc"><button class="btn btn-block btn-success btn-next" type="button" id="btnPlaceOrder" style='display:none'>PLACE ORDER &gt;&gt;</button></div>
			</div>
			<div class="tc"><img src="http://lottosocial.s3.amazonaws.com/cms2/wp-content/uploads/2015/07/cardIcons.png" alt="Card icons" ID='CardIconsimage' style='display:none'></div>
		</div>    
	</div>    
</form>