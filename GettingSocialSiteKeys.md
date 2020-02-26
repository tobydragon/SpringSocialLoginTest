Github:
https://github.com/settings/developers

google:
- Will only accept "top level domains" for URLs, so you need a tool to expose localhost as a top-level URL. To expose:
  - use localtest.me
    - redirects to localhost
    - documented here:
      - http://readme.localtest.me/
  - alternative lvh.me
    - documented here:
       - https://gist.github.com/levicook/563675
  - overkill ngrok:
    - download free version, follow instructions to set it running for 8080
    - difficult because it generates a new URL each time you start the software, meaning you need to update the google credentials page
    
