---
layout: page
title: Email Alerts
permalink: /email-alerts/
---

Fill out the form below if you would like to receive email alerts for new posts.

<form action="https://formspree.io/admin@elzahomestead.com" method="POST">
	<div class="input-field col s12">
		<input name="Name" id="fname" type="text" class="validate white-text">
		<label for="name">Name</label>
	</div>
	<div class="input-field col s12">
		<input name="Email" id="email" type="email" class="validate white-text">
		<label for="email" data-error="wrong" data-success="right">Email</label>
	</div>
	<div class="col s12">
		<label>Email Preferences</label>
		<select class="browser-default">
			<option value="posts" selected>Just Posts Alerts</option>
			<option value="posts and updates">Posts Alerts and Major Homestead Updates</option>
		</select>
	</div>
	<div class="input-field col s12">
		<button class="btn waves-effect waves-light green lighten-3" type="submit">Submit
			<i class="material-icons right">send</i>
		</button>
	</div>
</form>

