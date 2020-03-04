Github:
https://github.com/settings/developers

google:
https://console.developers.google.com/apis/credentials
- Will only accept "top level domains" for URLs, so you need a tool to expose localhost as a top-level URL. To expose:
  - using localtest.me
    - redirects to localhost
    - documented here:
      - http://readme.localtest.me/
  
  
  - alternative lvh.me
    - documented here:
       - https://gist.github.com/levicook/563675
  - alternative, change your hosts file to recognize a different URL
    - https://ktor.io/quickstart/guides/oauth.html
  - overkill ngrok:
    - download free version, follow instructions to set it running for 8080
    - difficult because it generates a new URL each time you start the software, meaning you need to update the google credentials page
- can't use username or email directly or it could be spoofed
  - instead, use fetched info to get a token
    - need an API
      - https://developers.google.com/api-client-library/java/google-api-java-client/setup#google-api-client
    - 
