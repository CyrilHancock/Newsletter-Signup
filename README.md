# Newsletter-Signup
## How it is made
  This Signup Website is made using HTML,CSS,BOOTSTRAP,JAVASCRIPT,NPM,NODE,EXPRESS,.
 The fonts are provided by "https://fonts.googleapis.com/"
 It uses MailChimp API to collect Email from Signup Users. 
## How to Download
Clone the repository by typing
```
git clone https://github.com/CyrilHancock/Newsletter-Signup.git
```
 Change process.env.PORT to 3000 in **app.js**.
 Register at MailChimp  and change the api key and server name in mailChimp.
  > mailchimp.setConfig
  >   1. ENTER YOUR API KEY HERE
  >    apiKey: your api key for mailchimp,
  >   2. ENTER YOUR API KEY PREFIX HERE i.e.THE SERVER
  >     server: server name at the end example us-14
> Also Change the List id to Your List id in Mail chimp.
 >    3. ENTER YOU LIST ID HERE
  >      const listId = list id 
           

For Running on Local

```
node app.js

And navigate to

http://localhost:3000
```
## See it Now
Visit "https://blooming-coast-27520.herokuapp.com/"

# Preview
![This is an image](/images/newslettersignup.png)

