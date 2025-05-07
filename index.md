<html>
  <body>
    <script type='text/javascript'>
    	function initEmbeddedMessaging() {
    		try {
    			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
    
    			embeddedservice_bootstrap.init(
    				'00DWU00000JUnUz',
    				'Test_Deployment',
    				'https://dwu00000junuz2al-dev-ed.develop.my.site.com/ESWTestDeployment1746642713076',
    				{
    					scrt2URL: 'https://dwu00000junuz2al-dev-ed.develop.my.salesforce-scrt.com'
    				}
    			);
    		} catch (err) {
    			console.error('Error loading Embedded Messaging: ', err);
    		}
    	};
    </script>
    <script type='text/javascript' src='https://dwu00000junuz2al-dev-ed.develop.my.site.com/ESWTestDeployment1746642713076/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
