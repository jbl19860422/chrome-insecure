# chrome-insecure
chrome做webrtc测试时，如果访问的是http，则需要特殊配置
配置属性如下：
```
"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --ignore-certificate-errors --unsafely-treat-insecure-origin-as-secure=http://172.19.5.123:3001 --user-data-dir=g:/temp2
```
