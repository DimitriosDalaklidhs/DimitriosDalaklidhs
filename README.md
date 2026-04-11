# Dimitrios Dalaklidis
Informatics student at the University of Western Macedonia, graduating soon with 197/240 ECTS. I work primarily in C and Java, with a focus on systems programming, network applications, and backend development. I am comfortable at the low level: sockets, process management, memory, file I/O. I also have experience building production structured backend applications with REST APIs, JWT security, role based access and database backends.
Open to roles in systems, backend, or software engineering.
&nbsp;

# Open Source Contributions
## ion-fusion/fusion-java (Amazon Ion):  [PR #490](https://github.com/ion-fusion/fusion-java/pull/490) · [PR #518](https://github.com/ion-fusion/fusion-java/pull/518)
- Fixed a bug in `ActualSymbol.write()` where operator symbols like `+` and `=` were incorrectly quoted inside sexp contexts, violating Ion spec behavior. Added test cases covering operator symbols, quoted symbols, null symbols, and improper sexps. Multi-round code review with project maintainers including a principal engineer with 20+ years at Amazon. 200+ lines accepted into main.
- Added `ionize(Object, IonWriter)` to the `TopLevel` public embedding API, placing ionization at the correct abstraction layer rather than `FusionRuntime`. Navigated package dependency constraints enforced by static analysis tooling, structural baseline maintenance, and Javadoc requirements for a public-facing interface. Reviewed and merged by Todd Jonker, co-inventor of Amazon Ion.
## Projects
**[Greek Hospital Management Spring Boot REST API](https://github.com/DimitriosDalaklidhs/spring-boot-Greek-hospital-system)** `Java` `Spring Boot` `MySQL` `JWT`
Secure REST API for managing hospital patients, hospitalizations, and medical tests. Features stateless JWT authentication, role based access control (DOCTOR / CLERK / ADMIN) enforced at the HTTP method level, and atomic patient registration via Spring `@Transactional`. Includes a full Luhn algorithm implementation for validating Greek ΑΜΚΑ numbers with birth date extraction. Deployed on Railway!

**[api-gateway](https://github.com/DimitriosDalaklidhs/api-gateway)** `Python` `FastAPI` `Docker` `Redis`
High performing API Gateway for routing requests to backend services with resilience and control features. Includes rate limiting (Redis sliding window with Lua), retries with exponential backoff, circuit breaker (CLOSED/OPEN/HALF-OPEN), JWT authentication, tested to ensure security and response caching. Provides admin endpoints for monitoring (metrics, circuit states, rate limits) and a mock service for failure injection and testing.

**[Library-System-Java-MySQL](https://github.com/DimitriosDalaklidhs/Library-System-Java-MySQL)** `Java` `MySQL`
Full library management system with SWING and MySQL backend. Features user authentication, book search, borrowed book tracking, and automated database initialization via SQL schemas.

**[process-supervisor](https://github.com/DimitriosDalaklidhs/process-supervisor)** `Bash` `Docker`
Lightweight process supervisor written in Bash for managing and automatically restarting long running workloads in Docker and Kubernetes environments.

**[tcp-prime-factors-server-client](https://github.com/DimitriosDalaklidhs/tcp-prime-factors-server-client)** `C`
TCP client server application. The client sends integers over a socket; the server computes and returns their prime factors. Built for a networking course at UowM.

**[GitProjectServer](https://github.com/DimitriosDalaklidhs/GitProjectServer)** `C` `Winsock`
Multithreaded HTTP server written from scratch using Windows sockets. Handles concurrent connections without a framework.

**[currency-exchange-server](https://github.com/DimitriosDalaklidhs/currency-exchange-server)** `C`
TCP/IP client server system for currency exchange operations. Focuses on protocol design and socket communication.

**[unix-process-management](https://github.com/DimitriosDalaklidhs/unix-process-management)** `C` `Unix` `IPC` `Docker`
Demonstrates Unix interprocess communication using a shared pipe across multiple child processes. Covers the full process lifecycle: creation, concurrent execution, and synchronization via fork(), getpid(), pipe(), and wait(). Packaged with a multi stage Docker build; no local C toolchain required.

&nbsp;
## Skills
`C` `Java` `Spring Boot` `Bash` `TCP/IP` `Unix` `MySQL` `Docker` `Kubernetes` `English C2 Michigan State University ECPE certified` `Git` `JWT` `REST APIs`
&nbsp;
## Contact
 dalaklidesdemetres@gmail.com
