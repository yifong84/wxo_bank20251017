<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "DTE_Bank_wxO.png"
    	width="auto" height="1200"
         alt = "New Watson Assistant Bank" />

</head>

<script>
  window.wxOConfiguration = {
    orchestrationID: "0781f29958be4f588e177e1250f85e99_891b1d17-e2e1-4d49-a4a0-13a0b07d4492",
    hostURL: "https://us-south.watson-orchestrate.cloud.ibm.com",
    rootElementID: "root",
    deploymentPlatform: "ibmcloud",
    crn: "crn:v1:bluemix:public:watsonx-orchestrate:us-south:a/0781f29958be4f588e177e1250f85e99:891b1d17-e2e1-4d49-a4a0-13a0b07d4492::",
    chatOptions: {
        agentId: "871aa964-789b-496f-8b00-e2c54ca8bb53", 
    }
  };
  setTimeout(function () {
    const script = document.createElement('script');
    script.src = `${window.wxOConfiguration.hostURL}/wxochat/wxoLoader.js?embed=true`;
    script.addEventListener('load', function () {
        wxoLoader.init();
    });
    document.head.appendChild(script);
  }, 0);                     
</script>

<body></body>

</html>
