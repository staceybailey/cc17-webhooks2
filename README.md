# cc17-webhooks2
Send first webhook to requestb.in<br/>
webhook to scripted rest api is added - just logging so far.<br/>
and now with the right Content type on the web hook <br/>
Webhook stream table is in place now <br/>
invalid table name - <br/>
added the second webhook to the table name <br/>
and finally with the workflow and notification. <br/>
and finally, finally with the secret.<br/>
Are we done? <br/> 
If I could spell, maybe we would have been. <br/>
argh.  still?
that .dataString was still in there. <br/>
    grWebhook.payload = request.body; <br/>
and now with  grWebhook.payload = request.body.dataString;
??
set to just body, which is declared at the top of the code.<br/> 
and final test with an invalid secret.
