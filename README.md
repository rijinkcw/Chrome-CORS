# Chrome-CORS
A demo vulnerable application for stealing sensitive  information by abusing Google Chrome cache. When `Access Control Allow Origin` header is set to `*` without having cache control response headers , an attacker can steal victim's private information.

##### Credentials
`Username : gamer`
`Password: gamer`

#### Solution
By using the `force-cache` directive in `fetch` function of js, we can ask the browser to first check if the request is cached and return the cached version if it exist.


Original bug report : https://bugs.chromium.org/p/chromium/issues/detail?id=988319

Reference : https://hackerone.com/reports/761726

Feel free to contact me over [Twitter](https://twitter.com/roughwire)

##### Made by 
[@roughwire](https://twitter.com/roughwire) & [@MrGeek_007](https://twitter.com/MrGeek_007)
