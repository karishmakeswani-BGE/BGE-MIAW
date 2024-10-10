<html>
	MIAW Iteration 34. 02/08/2024
	<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
				embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "Access_Token" : "8908aef1-2559-48d9-9c20-9f99992172f7", "Origin_Page" : "/home/my-accounts", "Session_Token" : "87e10251-3892-4add-8fce-c1af9aed77b3" });
			});
   
			embeddedservice_bootstrap.init(
				'00DUB000002gKO7',
				'MIAW_Bot',
				'https://bordgaisenergyeandu--karishbot.sandbox.my.site.com/ESWMIAWBot1723819197280',
				{
					scrt2URL: 'https://bordgaisenergyeandu--karishbot.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://bordgaisenergyeandu--karishbot.sandbox.my.site.com/ESWMIAWBot1723819197280/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

 	 </body>
</html>
