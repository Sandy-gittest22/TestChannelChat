<html>
  <body>
        <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DDI0000008jMw',
				'ServiceChat',
				'https://sellside--prjdev.sandbox.my.site.com/ESWTestChatBot1770134599021',
				{
					scrt2URL: 'https://sellside--prjdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://sellside--prjdev.sandbox.my.site.com/ESWTestChatBot1770134599021/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

    </body>
  </html>

    </body>
  </html>
