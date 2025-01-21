<html>
	MIAW Iteration 34. 02/08/2024
	<body>

<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'


			window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
				embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "Access_Token" : "8d62c7a9-53a4-439d-8644-75ba074bc63b", "Origin_Page" : "/home/my-accounts", "Session_Token" : "87e10251-3892-4add-8fce-c1af9aed77b3" });
			});

			
			embeddedservice_bootstrap.init(
				'00DRR00000DD6FR',
				'BGEKKWeb',
				'https://bordgaisenergyeandu--kkdev.sandbox.my.site.com/ESWBGEKKWeb1737462497269',
				{
					scrt2URL: 'https://bordgaisenergyeandu--kkdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://bordgaisenergyeandu--kkdev.sandbox.my.site.com/ESWBGEKKWeb1737462497269/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

	 </body>
</html>
