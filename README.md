# Dimitrios Dalaklidis
Graduate of the School of Sciences with a 4-year degree in Informatics from the public EU/Greek University of Western Macedonia (THE World University Rankings: Computer Science 601-800 for 2025). I work primarily in C and Java with a focus on systems programming and backend development. In addition, personal projects include work with sockets as well as POSIX, process management but also memory. I have experience building production-grade backend services with REST APIs, JWT auth, relational databases and much more while at the same time I am an open-source contributor to ion fusion (Amazon). Currently open to roles in systems, backend or software engineering.
&nbsp;

## Open Source Contributions
**ion-fusion/fusion-java (Amazon Ion):** [PR #490](https://github.com/ion-fusion/fusion-java/pull/490) · [PR #518](https://github.com/ion-fusion/fusion-java/pull/518) · [PR #521](https://github.com/ion-fusion/fusion-java/pull/521) 

- I fixed a bug in `ActualSymbol.write()` where operator symbols like `+` and `=` were incorrectly quoted inside sexp contexts thus violating Ion spec behavior. I then added test cases covering operator symbols, quoted symbols, null symbols and improper sexps to assert my code was behaving correctly. Went through rounds of code review with project maintainers including a principal engineer with 20+ years at Amazon named Todd Jonker. 200+ lines of my code were accepted into main.
- Added `ionize(Object, IonWriter)` to the `TopLevel` public embedding API, placing ionization at the correct abstraction layer rather than `FusionRuntime`. I had to navigate package dependency constraints enforced by static analysis tooling, structural baseline maintenance and Javadoc requirements for a public - facing interface. Reviewed and merged by Todd Jonker, co-inventor of Amazon Ion. 20+ lines this time were accepted into main.
- Centralized `FusionInterrupt` exception handling in the embedding layer; introduced `EvalTask<T>` functional interface and `withEvaluator()` helper on `StandardTopLevel`, eliminating repeated boilerplate across all call sites and fixing a missing interrupt catch in `StandardRuntime`. 70+ lines of clean code accepted into main.
## Projects
**[Greek Hospital Management Spring Boot REST API](https://github.com/DimitriosDalaklidhs/spring-boot-Greek-hospital-system)** `Java` `Spring Boot` `MySQL` `JWT` `JUnit`
Due to the recent shortages in the Greek healthcare system, I was inspired to create an original software that manages hospital patients to be used by clerks and Doctors alike. To that end, I used Secure REST API for said managing of patients, but also hospitalizations as well as medical tests. The software features stateless JsonWebToken authentication, role based access control (DOCTOR / CLERK / ADMIN) enforced at the HTTP method level and atomic patient registration(for every individual person that is) via Spring `@Transactional`. Lastly, It includes a full Luhn algorithm implementation for validating Greek ΑΜΚΑ numbers with birth date extraction. Last upgrades include unit tests with JUnit 5 and Mockito.

**[api-gateway](https://github.com/DimitriosDalaklidhs/api-gateway)** `Python` `FastAPI` `Docker` `Redis`
API Gateway for routing requests to backend services with resilience and control features. Includes rate limiting (Redis sliding window with Lua), retries with exponential backoff, circuit breaker (CLOSED/OPEN/HALF-OPEN), JWT authentication, tested to ensure security and response caching. Provides admin endpoints for monitoring (metrics, circuit states, rate limits) and a mock service for failure injection and testing. Built with the aim of easing the growing issues regarding traffic in large systems(ie Netflix type services).

**[Library-System-Java-MySQL](https://github.com/DimitriosDalaklidhs/Library-System-Java-MySQL)** `Java` `MySQL`
Full library management system with SWING and MySQL backend. Features user authentication, book search, borrowed book tracking and automated database initialization via SQL schemas. With this one, I wanted to prove that although I am a young engineer I can still work with legacy technology like SWING. 

**[unix-process-management](https://github.com/DimitriosDalaklidhs/unix-process-management)** `C` `Unix` `IPC` `Docker`
Beyond this programs obvious relevance to low-level building, It also showed me for the first time how we can reduce size by a big percentage using Docker something that is going to become ever more relevant in the years to come. Unix Process Management demonstrates Unix interprocess communication using a shared pipe across multiple child processes. Covers the full process lifecycle: creation, concurrent execution, and synchronization via fork(), getpid(), pipe(), and wait(). Packaged with a multi stage Docker build; no local C toolchain required. Using Docker we are able to reduce overall size by more than 70 percent and significantly reduce the attack surface. This repository was heavily inspired by the brilliant book of Andrew S. Tanenbaum and Herbert Bos."Modern Operating Systems".

&nbsp;
## Skills
`C` `Java` `Spring Boot` `Bash` `TCP/IP` `Unix` `MySQL` `Docker` `Kubernetes` `English C2 University of Michigan ECPE certified` `Git` `JWT` `REST APIs`
&nbsp;
## Contact
 dalaklidesdemetres@gmail.com
