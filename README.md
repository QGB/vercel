vercel 不支持 websocket
https://vercel.com/support/articles/do-vercel-serverless-functions-support-websocket-connections

U.stime(),U.sleep(9.9),U.stime()  还可以

U.stime(),U.sleep(9.999),U.stime() 总执行时间超过10秒，报错
```
This Serverless Function has timed out.

Your connection is working correctly.

Vercel is working correctly.

504: GATEWAY_TIMEOUT
Code: FUNCTION_INVOCATION_TIMEOUT
ID: hnd1::jjm5k-**
```
