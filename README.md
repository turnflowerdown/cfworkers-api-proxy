# cfworkers-api-proxy
https://github.com/tech-shrimp/deno-api-proxy 的cfworker部署版本  
![微信图片_20250202002004](https://github.com/user-attachments/assets/13fb2348-e3ce-47dd-8c17-9e94902977ed)
deno官方禁止转发代理，部署那个代理项目的deno账号全都封了  
用GPT微改了下原项目，适配了worker部署，直接把worker.js复制到worker部署就好，使用方法和原项目一样   
用 addEventListener('fetch') 代替了 Deno.serve()  ————这是deno的专有函数   
‼️‼️注意转发代理也是不符合cf用户协议的，见好就收   
