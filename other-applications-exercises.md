# Texas Cyber Summit - Other applications exercises

## Route detection



1. Make a fork of: https://github.com/Netflix/eureka
2. Set up this project in Semgrep App
3. Write a rule to detect JAX-RS routes, or use the following:  https://semgrep.dev/s/inkz:java-route-detection-1
4. From the editor, click **Add to policy** and add it to **Rule board - Audit column**
    1. [Optional] Go to **Settings → Integrations** and set up an email notification for yourself
    2. [Optional] Click the bell icon 🔔  on the **Audit** column and add this notification
5. Make a PR with a new route 
    1. (here for example https://github.com/Netflix/eureka/blob/50db5d24a7c45375c0b32fffa238256276e6432e/eureka-core/src/main/java/com/netflix/eureka/resources/ServerInfoResource.java  just copy paste one of the routes)
6. Wait for your notification (a PR comment or an email if you did the optional steps in step (4)



## Dependency modifications



1. Make a fork of: https://github.com/expressjs/serve-index
2. Set up this project in Semgrep App
3. Write a rule to detect JavaScript imports, or use the following: https://semgrep.dev/s/inkz:imports-js-1
4. From the editor, click **Add to policy** and add it to **Rule board - Audit column**
    1. [Optional] Go to **Settings → Integrations** and set up an email notification for yourself
    2. [Optional] Click the bell icon 🔔  on the **Audit** column and add this notification
5. Make a PR with a new dependency (here for example https://github.com/expressjs/serve-index/blob/master/index.js  just copy paste one of the `require` and change it to `foo` or `lodash`)
6. Wait for your notification (a PR comment or an email if you did the optional steps in step (4)

