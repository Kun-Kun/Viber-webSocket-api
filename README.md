# Viber-webSocket-api
Viber on PC create web socket server to interact with application via REST api:
Endpoint: ws://localhost:45112/viber

With headers:
accept-encoding: gzip, deflate, br
accept-language: ru-RU,ru;q=0.9,en-US;q=0.8,en;q=0.7
cookie: _ga=GA1.1.2115374939.1521454097
origin: chrome-extension://dafalpmmoljglecaoelijmbkhpdoobmm
user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/65.0.3325.181 Safari/537.36

Api allows to sent links, pictures, video to app:

{"message":"get_client_info","vesion":"1.0","data":{},"request_id":"1"}

{"message":"share","vesion":"1.0","data":{"type":"url","url":"https://www.google.com/","title":"Google","description":""},"request_id":"8"}

{"message":"share","vesion":"1.0","data":{"type":"image","image":"data:image/png;base64,iVBOR==","title":"Google","url":"https://www.google.com/"},"request_id":"2"}

{"message":"share","vesion":"1.0","data":{"description":"","type":"video","thumb":"data:image/png;base64,iVBOR==","title":"","url":"https://www.google.com/"},"request_id":"2"}

Ref:https://chrome.google.com/webstore/detail/viber/dafalpmmoljglecaoelijmbkhpdoobmm?utm_source=plus
