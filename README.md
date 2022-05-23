# ngrok
ngrok to make our pc public

1. Create an account on ngrok. 
Visit : https://dashboard.ngrok.com/
2. Download NGROK.tzg/zip 

3. Connect your account.

$ ngrok config add-authtoken 29I97F9aOFW2PfmDZTCg4FQXKPs_4NDx7JQQed6WgVDPJF4fQOR <br>
OR <br>
$ ngrok authtoken 29I97F9aOFW2PfmDZTCg4FQXKPs_4NDx7JQQed6WgVDPJF4fQOR  <br>

//Running this command will add your authtoken to the default ngrok.yml configuration file. This will grant you access to more features and longer session times.

4. To start a HTTP tunnel forwarding to your local port 80, run this:

$ ngrok http portnumber
eg : ngrok http 80
5. Run the python code in port 80

6. In ngrok we will get one link type that link in other network to get the page.

7. to check the status of ngrok - in browser url type http://127.0.0.1:4040 

8. to stop click - ctrl+c
