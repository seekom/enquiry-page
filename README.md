# iBex Enquiry Page
Simple enquiry page for the legacy iBex system.


## Sample Installation

```html
<!-- Begin iBex Enquiry iFrame Code -->
<iframe id="ibex-enquiry-page" name="" onload="iBexFrame.SetHeight(this);" src="" width="100%" height="600px" scrolling="auto" frameborder="no" style="border: none; overflow-y: visible"></iframe>
<script type="text/javascript">
	// EDIT HERE
	var ibOperatorID = 'arapawa'; // Your OperatorID
	var ibPropID = 5416; // Your PropertyID
	
	// The public URL pointing at your SeekomMessageAgent.html file
	var ibMsgAgentURL = 'http://example.com/my/path/to/ibex-message-agent.html';
	
	// This line activates the enquiry page. The passed in parameter must match the ID of the iFrame above
	iBexEnquiryFrameController.run('ibex-enquiry-page');
	
	// END EDITING (no need to edit any further)
</script>
<!-- End iBex Enquiry iFrame Code -->
```
