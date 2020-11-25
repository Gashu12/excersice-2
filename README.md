# excersice-2
## The similarities and differences between SpiderMonkey and V8
The biggest difference is in compilation. ***SpiderMonkey*** compiles JavaScript to an intermediate language which is interpreted. ***V8*** differs by compiling JavaScript to machine instructions, eliminating a need for an interpreter.
the similar aspects like:
* improving garbage collection and
* linearization, among many other optimizations


Actually, **Spidermonkey (FF)** and **V8 (Chrome)** are very ***similar in the core JavaScript engine API*** in that both try to be standards compliant. The main difference is that Spidermonkey tends to add some nice extras to their API if they feel it is needed. All of this is found at the Mozilla Development Center *(MDC)* for JavaScript and well documented if it is not a standard.



**Difference between Chrome V8 vs Mozilla’s Spider Monkey:** The main difference between chrome’s V8 Engine and Mozilla’s SpiderMonkey lies in ECMAScript conformance Test262 which is used to check how closely JavaScript implementation follows the ***ECMAScript 5th edition specification standards,*** created by ***ECMA International***. This test consists of thousands of individual tests, which checks the requirement of the specification.
Conformance test:
* Chrome’s V8 Engine -> 98%
* Mozilla’s SpiderMonkey -> 87%

*references*
1. [this link is from qoura](https://www.quora.com/How-do-V8-and-SpiderMonkey-differ)
2. [this is the link from webmaster](https://webmasters.stackexchange.com/questions/3/what-are-the-differences-between-firefoxs-javascript-engine-and-chromes-v8)
3. [this is the link from GeeksforGeeks](https://www.geeksforgeeks.org/what-happens-inside-javascript-engine/)
