# speechly-search-bar-velo
custom element code for adding a voice search to your velo site

This code is for use in a Velo enabled Wix site on a premium plan

You will need to update any element id's used in the code to match your use case.

You will also need to create your own Speechly App ID and store this in the Secrets Manager.
Speechly App ID creation: https://docs.speechly.com/examples/stt-only/
Secrets Manager: https://support.wix.com/en/article/velo-working-with-the-secrets-manager

Place this script in the head by going to your Wix Dashboard --> Settings --> Custom Code
<script type="text/javascript" src="https://unpkg.com/@speechly/browser-ui/core/push-to-talk-button.js"></script>

This code is all based on this example created by Speechly
https://codepen.io/speechly/pen/VwzoMrW?editors=1010
