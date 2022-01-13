## api-runner  
A Idea plugin that enables you to test your HTTP or Dubbo API quickly and easily. For developers to manually validate APIs without additional test code.  
#### plugin page: https://plugins.jetbrains.com/plugin/18357-api-runner
## Features
- HTTP/Dubbo Client: Simple way to do HTTP/Dubbo requests.
- Generate Tests In One Click: Automatically generate request from your source code for visual interaction, and easier to use. Supported framework: *Dubbo*、*SpringMVC*.
- Favourite And History Collections: Remember your every reqeust, save any requests for execution at any time.

## Quick Start
1. Right-click on one method that your want to test.
2. Select <b>Request As...</b>, choose Dubbo or HTTP request.
3. Change the request info in the ToolWindow if needed.
4. Click the Run button, then you can see the response in the right console.

## Other
### About Parser
- SpringMVC parser only support simple Annotation now: **@RequestMapping**, **@*Mapping**, **@RequestBody**.
- The parser's support for complex parameters is not complete enough. Like: **Multi-Level nested classes**, **Unusual Data Types**
