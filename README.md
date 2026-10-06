# Software Engineering Curriculum

**74 books · 16 sections · 5 phases**

A structured path from first principles to staff-level engineering, centered on the Java, Kotlin and Spring ecosystem, with deep coverage of distributed systems and engineering practice.

*Last updated: October 2026*

---

## Contents

| Phase | Sections | Focus |
|-------|----------|-------|
| 1. Foundations | 1–4 | Mathematics, computer systems, algorithms, networking |
| 2. Language and Craft | 5–7 | Java, Kotlin, concurrency, design, testing |
| 3. Backend Engineering | 8–9 | Spring, reactive programming, APIs, databases |
| 4. Architecture and Distributed Systems | 10–13 | DDD, microservices, messaging, architecture |
| 5. Production and Staff-Level Practice | 14–16 | Cloud native, reliability, engineering leadership |

**Sequencing note.** MIT 6.5840 (§11) lists 6.1800 or 6.1810 as prerequisites. Complete MIT 6.1810 (§2) or 6.1800 (§15) before starting it.

---

## Phase 1 · Foundations

### 1 · Mathematics, Logic and Probability

**Courses**

- [MIT 6.042J · Mathematics for Computer Science](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-spring-2015/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 1 | [Discrete Mathematics with Applications](https://openlibrary.org/isbn/9781337694193) | Susanna S. Epp | 5th ed. |
| 2 | [A Modern Introduction to Probability and Statistics](https://link.springer.com/book/10.1007/1-84628-168-7) | F.M. Dekking et al. | |

---

### 2 · Computer Systems and Hardware

**Courses**

- [CMU 15-213 · Introduction to Computer Systems](https://www.cs.cmu.edu/~213/)
- [UC Berkeley CS61C · Great Ideas in Computer Architecture](https://cs61c.org/)
- [MIT 6.1810 · Operating System Engineering](https://ocw.mit.edu/courses/6-1810-operating-system-engineering-fall-2023/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 3 | [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/) | Remzi & Andrea Arpaci-Dusseau | Free online |
| 4 | [Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/) | Bryant & O'Hallaron | |

---

### 3 · Algorithms and Data Structures

**Courses**

- [MIT 6.006 · Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/)
- Princeton Algorithms: [Part I](https://www.coursera.org/learn/algorithms-part1) · [Part II](https://www.coursera.org/learn/algorithms-part2)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 5 | [A Common-Sense Guide to Data Structures and Algorithms](https://pragprog.com/titles/jwdsal2/a-common-sense-guide-to-data-structures-and-algorithms-second-edition/) | Jay Wengrow | 2nd ed. |
| 6 | [The Algorithm Design Manual](https://www.algorist.com/) | Steven Skiena | |
| 7 | [Elements of Programming Interviews in Java](https://elementsofprogramminginterviews.com/) | Aziz, Lee & Prakash | |

---

### 4 · Networking and Linux Systems Programming

**Courses**

- [Stanford CS144 · Introduction to Computer Networking](https://cs144.github.io/)
- [UC Berkeley CS168 · Introduction to the Internet](https://cs168.io/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 8 | [Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/) | Kurose & Ross | |
| 9 | [The Linux Programming Interface](https://man7.org/tlpi/) | Michael Kerrisk | |

---

## Phase 2 · Language and Craft

### 5 · Java and Kotlin

**Courses**

- [UC Berkeley CS61B · Data Structures (Java)](https://sp21.datastructur.es/)
- [CMU 15-418 · Parallel Computer Architecture and Programming](http://15418.courses.cs.cmu.edu/)

**Core language**

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 10 | [Core Java, Vol. 1 — Fundamentals](https://horstmann.com/corejava/) | Cay S. Horstmann | |
| 11 | [Core Java, Vol. 2 — Advanced Features](https://horstmann.com/corejava/) | Cay S. Horstmann | |
| 12 | [Modern Java in Action](https://www.manning.com/books/modern-java-in-action) | Urma, Fusco & Mycroft | |
| 13 | [Effective Java](https://openlibrary.org/isbn/9780134685991) | Joshua Bloch | 3rd ed. |
| 14 | [Kotlin in Action](https://www.manning.com/books/kotlin-in-action-second-edition) | Aigner, Elizarov, Isakova & Jemerov | 2nd ed. |
| 15 | [The Joy of Kotlin](https://www.manning.com/books/the-joy-of-kotlin) | Pierre-Yves Saumont | |
| 16 | [Effective Kotlin](https://kt.academy/book/effectivekotlin) | Marcin Moskała | |

**Concurrency and performance**

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 17 | [Java Structured Concurrency](https://www.packtpub.com/en-us/product/java-structured-concurrency-9781806105021) | Anghel Leonard | Virtual threads, structured concurrency, scoped values |
| 18 | [Java Concurrency in Practice](https://openlibrary.org/isbn/9780321349606) | Brian Goetz et al. | |
| 19 | [Kotlin Coroutines Deep Dive](https://kt.academy/book/coroutines) | Marcin Moskała | |
| 20 | [Optimizing Cloud Native Java](https://www.oreilly.com/library/view/-/9781492039259/) | Evans, Gough & Newland | 2nd ed. |
| 21 | [Systems Performance](https://www.brendangregg.com/systems-performance-2nd-edition-book.html) | Brendan Gregg | 2nd ed. |

---

### 6 · Software Craftsmanship and Design

**Courses**

- [Stanford CS108 · Object-Oriented Systems Design](https://web.stanford.edu/class/cs108/)
- [MIT 6.102 · Software Construction](https://web.mit.edu/6.102/www/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 22 | [The Pragmatic Programmer](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/) | Hunt & Thomas | 20th anniversary ed. |
| 23 | [Clean Code](https://openlibrary.org/isbn/9780132350884) | Robert C. Martin | Read critically; pair with #28 |
| 24 | [Head First Design Patterns](https://openlibrary.org/isbn/9781492078005) | Freeman & Robson | 2nd ed. |
| 25 | [Refactoring](https://martinfowler.com/books/refactoring.html) | Martin Fowler | 2nd ed. |
| 26 | [Clean Architecture](https://openlibrary.org/isbn/9780134494166) | Robert C. Martin | |
| 27 | [Working Effectively with Legacy Code](https://openlibrary.org/isbn/9780131177055) | Michael Feathers | |
| 28 | [A Philosophy of Software Design](https://web.stanford.edu/~ouster/cgi-bin/book.php) | John Ousterhout | |

---

### 7 · Testing

**Courses**

- [CMU 17-214 · Principles of Software Construction](https://www.cs.cmu.edu/~schneide/17214/sp23/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 29 | [Test-Driven Development by Example](https://openlibrary.org/isbn/9780321146533) | Kent Beck | |
| 30 | [Unit Testing Principles, Practices, and Patterns](https://www.manning.com/books/unit-testing) | Vladimir Khorikov | |
| 31 | [Effective Software Testing](https://www.manning.com/books/effective-software-testing) | Mauricio Aniche | |
| 32 | [Pragmatic Unit Testing in Java with JUnit](https://pragprog.com/titles/utj3/pragmatic-unit-testing-in-java-with-junit-third-edition/) | Jeff Langr | 3rd ed. (2024) |

---

## Phase 3 · Backend Engineering

### 8 · Spring Framework, Reactive Programming and APIs

**Courses**

- [Spring Academy (official)](https://spring.academy/)
- [Stanford CS142 · Web Applications](https://web.stanford.edu/class/cs142/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 33 | [Spring in Action](https://www.manning.com/books/spring-in-action-sixth-edition) | Craig Walls | 6th ed. |
| 34 | [Modern API Development with Spring 6 and Spring Boot 3](https://www.packtpub.com/en-us/product/modern-api-development-with-spring-6-and-spring-boot-3-9781804613276) | Sourabh Sharma | |
| 35 | [Pro Spring 6](https://link.springer.com/search?query=Pro+Spring+6+Schaefer) | Schaefer & Ho | |
| 36 | [Spring Security in Action](https://www.manning.com/books/spring-security-in-action-second-edition) | Laurențiu Spilcă | 2nd ed. |
| 37 | [gRPC: Up and Running](https://openlibrary.org/isbn/9781492058335) | Indrasiri & Kuruppu | |
| 38 | [Reactive Spring](https://reactivespring.io/) | Josh Long | WebFlux, R2DBC, RSocket; pair with the official Reactor and Spring reference docs |

---

### 9 · Data-Intensive Systems and Databases

**Courses**

- [CMU 15-445 · Database Systems](https://15445.courses.cs.cmu.edu/)
- [UC Berkeley CS186 · Introduction to Database Systems](https://cs186berkeley.net/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 39 | [The Art of PostgreSQL](https://theartofpostgresql.com/) | Dimitri Fontaine | |
| 40 | [High-Performance Java Persistence](https://vladmihalcea.com/books/high-performance-java-persistence/) | Vlad Mihalcea | |
| 41 | [Understanding Distributed Systems](https://understandingdistributedsystems.com/) | Roberto Vitillo | |
| 42 | [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781098119058/) | Martin Kleppmann & Chris Riccomini | 2nd ed. (2026) |
| 43 | [Database Internals](https://www.oreilly.com/library/view/-/9781492040330/) | Alex Petrov | |

---

## Phase 4 · Architecture and Distributed Systems

### 10 · Domain-Driven Design

**Courses:** none. This topic is book-driven.

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 44 | [Learning Domain-Driven Design](https://www.oreilly.com/library/view/-/9781098100124/) | Vlad Khononov | Start here |
| 45 | [Implementing Domain-Driven Design](https://openlibrary.org/isbn/9780321834577) | Vaughn Vernon | |
| 46 | [Domain-Driven Design](https://www.domainlanguage.com/ddd/) | Eric Evans | Reference |

---

### 11 · Microservices

**Courses**

- [MIT 6.5840 · Distributed Systems](https://pdos.csail.mit.edu/6.824/) (formerly 6.824)
- [Stanford CS244B · Distributed Systems](https://cs244b.stanford.edu/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 47 | [Building Microservices](https://samnewman.io/books/building_microservices_2nd_edition/) | Sam Newman | 2nd ed. |
| 48 | [Microservices with Spring Boot and Spring Cloud](https://openlibrary.org/search?q=Microservices+with+Spring+Boot+and+Spring+Cloud+Magnus+Larsson) | Magnus Larsson | |
| 49 | [Microservices Patterns](https://microservices.io/book) | Chris Richardson | |

---

### 12 · Stream Processing and Messaging

**Courses**

- [Confluent Developer · Kafka courses](https://developer.confluent.io/courses/)
- MIT 6.5840 — see §11

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 50 | [Enterprise Integration Patterns](https://www.enterpriseintegrationpatterns.com/) | Hohpe & Woolf | |
| 51 | [Kafka: The Definitive Guide](https://www.confluent.io/resources/ebook/kafka-the-definitive-guide-v2/) | Shapira, Palino, Sivaram & Petty | 2nd ed.; free from Confluent |
| 52 | [Kafka Streams in Action](https://www.manning.com/books/kafka-streams-in-action-second-edition) | Bill Bejeck | 2nd ed. |
| 53 | [Building Event-Driven Microservices](https://www.oreilly.com/library/view/-/9781492057888/) | Adam Bellemare | |
| 54 | [Event Streams in Action](https://www.manning.com/books/event-streams-in-action) | Dean & Crettaz | |

---

### 13 · Software Architecture

**Courses:** see §6 (MIT 6.102) and §7 (CMU 17-214).

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 55 | [Fundamentals of Software Architecture](https://openlibrary.org/search?q=Fundamentals+of+Software+Architecture+Richards+Ford) | Richards & Ford | 2nd ed. |
| 56 | [API Design Patterns](https://www.manning.com/books/api-design-patterns) | J.J. Geewax | |
| 57 | [Patterns of Enterprise Application Architecture](https://martinfowler.com/books/eaa.html) | Martin Fowler | |
| 58 | [Building Evolutionary Architectures](https://evolutionaryarchitecture.com/) | Ford, Parsons, Kua & Sadalage | 2nd ed. |
| 59 | [Building Secure and Reliable Systems](https://sre.google/books/building-secure-reliable-systems/) | Adkins et al. (Google) | Free online |

---

## Phase 5 · Production and Staff-Level Practice

### 14 · Cloud Native, Containers and DevOps

**Courses**

- [CMU 15-719 · Advanced Cloud Computing](http://www.cs.cmu.edu/~15719/)
- [Linux Foundation · Introduction to Kubernetes (free)](https://training.linuxfoundation.org/training/introduction-to-kubernetes/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 60 | [Docker: Up & Running](https://www.oreilly.com/library/view/-/9781098131814/) | Kane & Matthias | 3rd ed. |
| 61 | [Continuous Delivery](https://continuousdelivery.com/) | Humble & Farley | |
| 62 | [AWS in Action](https://www.manning.com/books/amazon-web-services-in-action-third-edition) | Michael & Andreas Wittig | 3rd ed. |
| 63 | [Kubernetes: Up & Running](https://www.oreilly.com/library/view/-/9781098110192/) | Burns, Beda, Hightower & Evenson | 3rd ed. |
| 64 | [Kubernetes Patterns](https://k8spatterns.io/) | Ibryam & Huß | 2nd ed. |
| 65 | [Production Kubernetes](https://www.oreilly.com/library/view/-/9781492092292/) | Rosso, Lander, Brand & Harris | |
| 66 | [Observability Engineering](https://www.oreilly.com/library/view/-/9781492076438/) | Majors, Fong-Jones & Miranda | |
| 67 | [OAuth 2 in Action](https://www.manning.com/books/oauth-2-in-action) | Richer & Sanso | |

---

### 15 · Reliability and System Design

**Courses**

- [MIT 6.1800 · Computer Systems Engineering](https://web.mit.edu/6.1800/www/)
- [MIT 6.858 · Computer Systems Security](https://ocw.mit.edu/courses/6-858-computer-systems-security-fall-2014/)

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 68 | [System Design Interview: Volume 1](https://bytebytego.com/) | Alex Xu | |
| 69 | [System Design Interview: Volume 2](https://bytebytego.com/) | Alex Xu & Sahn Lam | |
| 70 | [Release It!](https://pragprog.com/titles/mnee2/release-it-second-edition/) | Michael Nygard | 2nd ed. |
| 71 | [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/) | Beyer et al. (Google) | Free online |

---

### 16 · Engineering Practice and Staff-Level Leadership

**Courses:** none. This topic is book-driven.

| # | Title | Author(s) | Notes |
|---|-------|-----------|-------|
| 72 | [Software Engineering at Google](https://abseil.io/resources/swe-book) | Winters, Manshreck & Wright | Free online |
| 73 | [The Staff Engineer's Path](https://www.oreilly.com/library/view/-/9781098118723/) | Tanya Reilly | |
| 74 | [Accelerate](https://itrevolution.com/product/accelerate/) | Forsgren, Humble & Kim | Optional |

---

*Memento Mori. Memento Vivere.*
