# AppSecCheatsheet
Cheatsheet I gather from my work experience and other sources

## Modern SSRF

# cheatsheet from @madrobot

https://medium.com/@madrobot/ssrf-server-side-request-forgery-types-and-ways-to-exploit-it-part-2-a085ec4332c0

## Extract URL from JS

### Angular 1-liner
CC @JaneScott_ @Jiab77 @haxel0rd @0x616e6479
```sh
curl -s $URL | grep -Po "(\/)((?:[a-zA-Z\-_\:\.0-9\{\}]+))(\/)*((?:[a-zA-Z\-_\:\.0-9\{\}]+))(\/)((?:[a-zA-Z\-_\/\:\.0-9\{\}]+))" | sort -u
```
