- 👋 Hi, I’m @amanyadav986
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
amanyadav986/amanyadav986 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
/bin/bash -c "$(curl -fsSL https://php.new/install/mac/8.4)"
composer global require laravel/installer
laravel new example-app
 Composer provides a convenient, automatically generated class loader for

| this application. We just need to utilize it! We'll simply require it

| into the script here so we don't need to manually load our classes.

|

*/




require __DIR__.'/../vendor/autoload.php';



/*

|--------------------------------------------------------------------------

| Run The Application

|--------------------------------------------------------------------------

|

| Once we have the application, we can handle the incoming request using

| the application's HTTP kernel. Then, we will send the response back

| to this client's browser, allowing them to enjoy our application.

|

*/



$app = require_once __DIR__.'/../bootstrap/app.php';



$kernel = $app->make(Kernel::class);



$response = $kernel->handle(

    $request = Request::capture()

)->send();



$kernel->terminate($request, $response);

Request
Browser
Headers
Body
Context
Versions
Request
https://skilljs.site/password
GET
curl "https://skilljs.site/password" \
   -X GET \
   -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
   -H 'upgrade-insecure-requests: 1' \
   -H 'sec-ch-ua-platform: "Windows"' \
   -H 'sec-ch-ua-mobile: ?0' \
   -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
   -H 'accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7' \
   -H 'connection: Keep-Alive' \
   -H 'sec-fetch-site: cross-site' \
   -H 'cf-ipcountry: IN' \
   -H 'cf-connecting-ip: 103.199.205.168' \
   -H 'sec-fetch-mode: navigate' \
   -H 'sec-fetch-user: ?1' \
   -H 'cf-visitor: {"scheme":"https"}' \
   -H 'sec-fetch-dest: document' \
   -H 'cdn-loop: cloudflare; loops=1' \
   -H 'x-forwarded-proto: https' \
   -H 'accept-language: en-US,en;q=0.9' \
   -H 'accept-encoding: gzip, br' \
   -H 'priority: u=0, i' \
   -H 'host:amanyadav986 .site' \
   -H 'x-forwarded-for: 103.199.205.168' \
   -H 'cf-ray: 93853456cabc2ace-MRS';

Browser
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36

Headers
user-agent
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36

upgrade-insecure-requests
1

sec-ch-ua-platform
"Windows"

sec-ch-ua-mobile
?0

sec-ch-ua
"Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"

accept
text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7

connection
Keep-Alive

sec-fetch-site
cross-site

cf-ipcountry
IN

cf-connecting-ip
103.199.205.168

sec-fetch-mode
navigate

sec-fetch-user
?1

cf-visitor
{"scheme":"https"}

sec-fetch-dest
document

cdn-loop
cloudflare; loops=1

x-forwarded-proto
https

accept-language
en-US,en;q=0.9

accept-encoding
gzip, br

priority
u=0, i

host
skilljs.site

x-forwarded-for
103.199.205.168

cf-ray
93853456cabc2ace-MRS

