## api-runner  
A Idea plugin that enables you to test your HTTP or Dubbo API quickly and easily. For developers to manually validate APIs without additional test code.  
#### plugin page: https://plugins.jetbrains.com/plugin/18357-api-runner
## Features
- HTTP/Dubbo Client: Simple way to do HTTP/Dubbo requests.
- Generate Tests In One Click: Automatically generate request from your source code for visual interaction, and easier to use. Supported framework: *Dubbo*、*SpringMVC*.
- Favourite And History Collections: Remember your every reqeust, save any requests for execution at any time.
- Batch Execution: You can execute all APIs in the collection at once.

## Quick Start
1. Right-click on one method that your want to test.
2. Select <b>Request As...</b>, choose Dubbo or HTTP request.
3. Change the request info in the ToolWindow if needed.
4. Click the Run button, then you can see the response in the right console.
![init](https://github.com/cadeeper/cd-api-runner/blob/main/init.jpg?raw=true)
![choose](https://github.com/cadeeper/cd-api-runner/blob/main/choose.jpg?raw=true)
![call](https://github.com/cadeeper/cd-api-runner/blob/main/call.jpg?raw=true)
![saveApi](https://github.com/cadeeper/cd-api-runner/blob/main/saveApi.jpg?raw=true)
![history](https://github.com/cadeeper/cd-api-runner/blob/main/history.jpg?raw=true)
![customHeader](https://github.com/cadeeper/cd-api-runner/blob/main/customHeader.jpg?raw=true)

## Other
### About Parser
- SpringMVC parser only support simple Annotation now:  **@RequestMapping**, **@\*Mapping**, **@RequestBody**.
- The parser's support for complex parameters is not complete enough. Like: **Multi-Level nested classes**, **Unusual Data Types**
