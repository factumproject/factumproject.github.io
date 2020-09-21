---
layout: default
title: Contact
---
<div class="row">
	<div class="column column-80 column-offset-10">
		<form method="post" action="https://formspree.io/contact@factumproject.com">
			<fieldset>
				<input type="text" name="_gotcha" style="display:none" />
				<input type="hidden" name="_subject" value="Contact Form" />
				<input type="hidden" name="_next" value="http://www.factumproject.com/" />
				<label for="name">Name</label>
				<input placeholder="Full Name" name="name" id="name" type="text" />
				<label for="email">Email</label>
				<input placeholder="you@domain.com" name="email" id="email" type="email" />
				<label for="comment">Comment</label>
				<textarea placeholder="We need help getting our project done!" name="comment" id="comment"></textarea>
				<input class="button-primary" value="Comment" type="submit" />
			</fieldset>
		</form>
	</div>
</div>
