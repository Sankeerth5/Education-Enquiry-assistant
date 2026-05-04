# Education-Enquiry-assistant
Education Enquiry assistant is a Ai based assistant that help the students to know about the course and it details clearly it is web based chatbot
note : "I don't have a meta business account so am not able to do whatsapp based automation"
so I emmbeded into a website as a chatbot

here I am giving the backend file of the website and N8N Workflow file 

## How To Setup

In the N8N you need to add Your the gemini API KEY to test the workflow

And after activate the workflow you need to copy the production URL and paste it in the backend file
add it in this line 'YOUR_PRODUCTION_WEBHOOK_URL'

	createChat({
		webhookUrl: 'YOUR_PRODUCTION_WEBHOOK_URL' 
	});
</script>


