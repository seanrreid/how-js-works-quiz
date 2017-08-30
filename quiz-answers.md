[https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)

1) What is one example of the Javascript Engine?

  * V8 Engine - Chrome - powers Node.js
  * SpiderMonky - Firefox
  * Chakra - Microsoft Edge

2) What are the 2 main parts of the Javascript Engine?

  * Memory Heap
  * Call Stack

3) What provides the runtime API to the JS Engine? (i.e. Where does setTimeout come from?)
  
  * Web APIs are provided by the browser

4) Is JS single or multi-threaded?

  * JS is single threaded, it uses a single Call Stack

5) What is the Call Stack?
  
  * "The Call Stack is a data structure which records basically where in the program we are.”

6) What is “blowing the stack?”

  * Essentially, the Call Stack is overloaded. Usually caused by bad recursion

7) What happens to the browser when it’s processing the functions in the Call Stack

  * It’s blocked until the functions are finished.

8) What is the recommended way of executing complex functions wihout render blocking?

  * Asynchronous Callbacks