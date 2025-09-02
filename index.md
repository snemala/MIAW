<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Daj00000ZHYlu',
				'Web_Chat',
				'https://gerent-bb-dev-ed.develop.my.site.com/ESWWebChat1756825429502',
				{
					scrt2URL: 'https://gerent-bb-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://gerent-bb-dev-ed.develop.my.site.com/ESWWebChat1756825429502/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
