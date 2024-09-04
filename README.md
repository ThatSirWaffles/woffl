# woffl

Hey, I go by <b>Sir Waffles</b> on most platforms, branding my content under <b>woffl</b>. I'm a French guy, fluent in English and Russian, based in the UK, developing & designing actively since 2021. I'll respond fastest on Discord, details [here](contact).

<br/>
<p style="text-align: center"><i>UK time is <code><span id="time"></span></code></i></p>

<script>
	function updateTime() {
		const now = new Date();
		const options = {
			timeZone: 'Europe/London',
			hour: '2-digit',
			minute: '2-digit',
			second: '2-digit',
			hour12: false
		};
		const ukTime = now.toLocaleTimeString('en-GB', options);
		document.getElementById('time').textContent = ukTime;
	}
	setInterval(updateTime, 1000);
	window.onload = updateTime;
</script>