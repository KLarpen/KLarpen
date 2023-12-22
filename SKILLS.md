# Personal profile of software engineering skills

⬜ Optional, 🟦 Required, 🟩 Learned, 🟥 Declined

## Fundamental concepts

| Syntax               | Statements            | Functions             | Data structures     | Process & style      |
|----------------------|-----------------------|-----------------------|---------------------|----------------------|
| 🟩 value             | 🟩 if                 | 🟩 recursion          | 🟩 array            | 🟩 refactoring       |
| 🟩 identifier        | 🟩 loops              | 🟩 function           | 🟩 instance         | 🟩 code review       |
| 🟩 variable          | 🟩 assignment         | 🟩 return             | 🟩 object           | 🟩 antipatterns      |
| 🟩 constant          | 🟩 prototype          | 🟩 signature          | 🟩 collection       | 🟩 paradigm          |
| 🟩 scalar            | 🟩 class              | 🟩 argument           | 🟩 hash table       | 🟩 algorithm         |
| 🟩 literal           | 🟩 while              | 🟩 parameter          | 🟩 linked list      | 🟩 magic numbers     |
| 🟩 expression        | 🟩 do..while          | 🟩 pure function      | 🟩 queue            | 🟩 hardcode          |
| 🟩 heap              | 🟩 for                | 🟩 lambda             | 🟩 stack            | 🟩 complexity        |
| 🟩 type              | 🟩 for..in            | 🟩 side effects       | 🟩 deque            | 🟩 decomposition     |
| 🟩 primitive types   | 🟩 for..of            | 🟩 closure            | 🟩 serialization    | 🟩 spaghetti         |
| 🟩 reference         | 🟩 for await          | 🟩 partial            | 🟩 mixin, extend    | 🟩 silver bullet     |
| 🟩 flag              | 🟩 throw              | 🟩 currying           | 🟩 iterator         | 🟩 not invented here |
| 🟩 lexical scope     | 🟩 try..catch         | 🟩 chaining           | 🟩 typed arrays     | 🟩 dead code         |
| 🟩 code block        | 🟩 equality operators | 🟩 higher order       | 🟩 Map              | 🟩 unreachable code  |
| 🟩 Object            | 🟩 logical operators  | 🟩 callback           | 🟩 Set              | 🟩 duplicate code    |
| 🟩 this              | 🟩 bitwise operators  | 🟩 listener           | 🟩 weak collections | 🟩 exception         |
| 🟩 arrow function    | 🟩 break, continue    | 🟩 pipe               | 🟩 Proxy            | 🟩 return early      |
| 🟩 generator         | 🟩 switch             | 🟩 compose            | 🟩 Symbol           | 🟩 linter            |
| 🟩 async function    | 🟩 new Error          | 🟩 memoize            | 🟩 string parsing   | 🟩 prettier          |
| 🟩 call, bind, apply |                       | 🟩 factory            | 🟩 timers           | 🟩 unit test         |
| 🟩 Array             |                       | 🟩 pool               | 🟩 EventEmitter     | 🟩 git               |
| 🟩 instanceof        |                       | 🟩 wrapper            | 🟩 RegExp           | 🟩 GitHub            |
| 🟩 ...spread         |                       | 🟩 default parameters | 🟩 global           | 🟩 GitLab            |
| 🟩 ...rest           |                       |                       | 🟩 undefined        | 🟩 nvm               |
| 🟩 typeof            |                       |                       | 🟩 null             | 🟩 npm & yarn        |

## Multi-paradigm programming

| Theory                         | OOP basics            | Abstractions         | Patterns                 |
|--------------------------------|-----------------------|----------------------|--------------------------|
| 🟩 Procedural programming      | 🟩 constructor        | 🟩 struct, record    | 🟩 Singleton             |
| 🟩 Imperative programming      | 🟩 new                | 🟩 Mutable state     |                          |
| 🟩 Structured programming      | 🟩 Static method      | 🟩 Immutable state   |                          |
| 🟩 Non-structured programming  | 🟩 Method             | 🟩 Enum              |                          |
| 🟩 Functional programming      | 🟩 Async method       | 🟩 Linked list       |                          |
| 🟩 Prototype-based programming | 🟩 Getters, Setters   | 🟩 Doubly list       |                          |
| 🟩 Object-oriented programming | 🟩 Public fields      | 🟦 Unrolled list     |                          |
| ⬜ Object-based programming    | 🟩 Private fields     | 🟦 Circular list     |                          |
| 🟩 Generic programming         | 🟩 Field declarations | 🟩 Trees             |                          |
| 🟩 Concurrent computing        | 🟩 Inheritance        | 🟩 Graphs            |                          |
| 🟩 Asynchronous programming    | 🟩 Parent class       | 🟦 Functor           |                          |
| 🟩 Parallel programming        | 🟩 Polymorphism       | 🟦 Functional object |                          |
| 🟩 Reactive programming        | 🟩 Abstract class     | ⬜ Monad             |                          |
| 🟩 FRP (Functional-reactive)   | 🟩 Interface          | 🟩 Generator         |                          |
| 🟩 Automata-based programming  | 🟩 Encapsulation      | 🟩 Iterator          |                          |
| 🟩 Domain-specific languages   | 🟩 Hidden class       | 🟩 Async Iterator    |                          |
| 🟩 Multi-paradigm programming  | ⬜ Object form        |                      |                          |
| 🟩 Metaprogramming             | 🟩 instance           |                      |                          |
| 🟩 Actor model                 | 🟩 Introspection      |                      |                          |
|                                | 🟩 Reflection         |                      |                          |

## Asynchronous programming

| Async contracts        | JavaScript & Node.js specific  | Theory              | Techniques               |
|------------------------|--------------------------------|---------------------|--------------------------|
| 🟩 Callback-last       | 🟩 Timers                      | 🟩 Event Loop       | ⬜ Async composition     |
| 🟩 Error-first         | 🟩 setImmediate                | 🟩 Async error      | ⬜ Rx.js                 |
| 🟩 Promise             | 🟩 nextTick                    | 🟩 try..catch       | 🟦 Sequential async      |
| 🟩 Async function      | 🟩 AbortController             | 🟩 Non-blocking     | 🟦 Parallel async        |
| 🟩 await               | 🟩 Promise unhandled rejection | 🟩 Async I/O        | 🟩 Promise.all           |
| 🟩 Generator           | 🟦 Promise double resolve      | 🟦 Pattern Reactor  | 🟩 Promise.allSettled    | 
| 🟩 Async Generator     | 🟩 child_process               | 🟩 CAS operations   | 🟩 Promise.race          |
| 🟩 Async Iterator      | 🟩 worker_threads              | ⬜ epoll            | 🟩 Promise.any           |
| 🟩 Thenable            | 🟩 Atomics                     | ⬜ kqueue           | ⬜ Web Locks API         |
| 🟩 EventEmitter        | 🟩 Blocking operations         | ⬜ Completion ports | ⬜ Async Pool            | 
| ⬜ Cancelable callback | 🟦 Non-blocking loop for Array | ⬜ Event ports      | 🟩 Thread Pool           |
| ⬜ Cancelable Promise  | ⬜ High resolution clock       | 🟩 libuv            | 🟩 callbackify           |
| 🟦 Asynchronous Queue  | 🟩 Callback hell               | 🟩 Race conditions  | 🟩 promisify             |
| 🟩 Future              | 🟩 Promise hell                | 🟩 Dead locks       | 🟩 IPC                   | 
| ⬜ Deferred            |                                | 🟩 Live locks       | 🟩 Channel API           |
| 🟩 Observer            |                                | 🟩 Actor Model      | 🟩 Revealing Constructor |
| ⬜ Async Collector     |                                |                     |                          | 
| ⬜ Coroutine           |                                |                     |                          |
| ⬜ Goroutine           |                                |                     |                          |

## Node.js and backend

| Internals            | Theory                       | Network           | Technique        | Problems             |
|----------------------|------------------------------|-------------------|------------------|----------------------|
| 🟩 Nonblocking I/O   | 🟩 I/O bound tasks           | 🟩 HTTP(S)        | 🟩 Logging       | 🟩 Memory leaks      |
| 🟩 Event Loop        | 🟩 CPU bound tasks           | 🟩 TCP/SSL        | 🟩 Testing       | 🟩 Resource leaks    |
| 🟩 commonjs          | 🟩 Memory bound tasks        | 🟩 UDP            | ⬜ CI/CD         | 🟩 Blocking code     |
| 🟩 ECMA modules      | 🟩 Multilayer approach       | 🟩 TLS            | 🟩 Readable      | 🟩 Data race         |
| 🟩 Network API       | 🟩 Separation of concerns    | 🟩 Websocket      | 🟩 Writable      | 🟩 Graceful Shutdown |
| ⬜ Addons            | 🟩 Inversion of control      | 🟩 SSE            | 🟩 Transform     | 🟩 Dependencies      |
| ⬜ N-API             | 🟩 Dependency injection      | ⬜ HTTP/3 (QUIC)  | 🟩 back pressure |                      |
| ⬜ Webassembly       | 🟩 GRASP for JS and Node.js  | 🟩 Long polling   | 🟩 Buffer        |                      |
| 🟩 npm               | 🟩 SOLID for JS and Node.js  | 🟩 REST           | 🟩 Console       |                      |
| 🟩 node_modules      | 🟦 GoF for JS and Node.js    | 🟩 RPC            | 🟦 Inspector     |                      |
| 🟩 package.json      | 🟩 Distributed systems       | 🟩 Routing        | 🟩 Reliability   |                      |
| 🟩 vm isolation      | ⬜ Highload applications     | 🟩 IP sticky      | 🟩 Quality       |                      |
| 🟦 command line args | 🟩 DDD                       | 🟩 DoS            | 🟩 Availability  |                      |
| ⬜ Node.js CLI       | 🟩 Clean architecture        | 🟩 DDoS           | 🟩 Flexibility   |                      |
| 🟩 Streams           | 🟩 Domain in the middle      | 🟩 XSS            |                  |                      |
| 🟦 Clustering        | 🟩 Message Queue             | 🟩 Path traversal |                  |                      |
| 🟩 Load balancing    | 🟩 Transport-agnostic server | 🟩 CSRF           |                  |                      |
| ⬜ Serverless clouds | 🟩 Framework-agnostic app    | 🟩 DNS            |                  |                      |
| ⬜ FaaS clouds       | ⬜ Interactive applications  | 🟩 Fetch          |                  |                      |
| 🟩 Debugging node.js | ⬜ Real-time applications    | 🟦 zlib           |                  |                      |
| 🟩 crypto            | 🟩 CQS and CQRS              |                   |                  |                      |
| 🟩 SharedArrayBuffer | 🟩 Event Sourcing            |                   |                  |                      |
| 🟩 child_process     | 🟩 Shared memory             |                   |                  |                      |
| 🟩 worker_threads    |                              |                   |                  |                      |

## Other skills

- ⬜ Cybersecurity
- 🟩 TDD
- 🟩 Quality control
- ⬜ High-performance computing
- ⬜ Edge computing
- ⬜ Data warehouse
- ⬜ Low-code and no-code platforms
