# Hi, I'm Daniel Loki

I'm a Computer Science Engineering (BSc) student at Széchenyi István University, and before that I
spent five years in a software developer and tester programme. That order matters to me: I learned
to test software before I learned to build larger systems, so I tend to think about how something
can fail and how it can be verified, not only about whether it runs.

Most of my work is **backend development**. I build REST APIs with C# and ASP.NET Core on top of
relational databases, in containerised environments with CI pipelines around them. I also work with
React and TypeScript on the frontend, and I use Python for automation, scripting and machine
learning experiments. I am currently learning Java and Spring Boot, which map closely onto what I
already do in ASP.NET Core.

I like projects that are small enough to understand completely, but real enough to have constraints:
validation that actually rejects bad input, tests that actually catch regressions, and code that the
next person can read.

Currently looking for a one-year internship in backend development or testing.

## What I work with

**Languages** C#, Python, TypeScript, JavaScript, SQL, C, C++, Rust

**Backend** ASP.NET Core, REST APIs, Entity Framework

**Frontend** React, TypeScript, Angular basics

**Data** PostgreSQL, Microsoft SQL Server, EF migrations

**Testing** unit testing (xUnit, NUnit, MSTest), integration testing, Selenium WebDriver, test
case design, manual and exploratory testing, regression testing, issue tracking

**Tooling** Docker, GitHub Actions, CI/CD, Git, Linux CLI, Postman

## Featured projects

**[qa-portfolio](https://github.com/justhurky/qa-portfolio)** · xUnit, NUnit, Selenium WebDriver,
manual and exploratory testing, k6
A worked example of software testing rather than a pile of assertions: 40 numbered requirements, test
cases derived from them with boundary value analysis, a decision table and state transition coverage,
then 251 automated tests across unit, integration, browser and performance layers, alongside scripted
manual cases and session based exploratory charters. Four defects were found, reproduced and written
up, two of them by hand under a green automated suite; the tests that expose the open ones are tagged
so the build gate stays honest instead of green by deletion.

**[aorta_student](https://github.com/justhurky/aorta_student)** · Python, YOLOv8, DICOM
Computer vision pipeline that reads raw DICOM medical imaging files, detects measurement endpoints
with a custom-trained model, converts the result into real-world distances and generates PDF
reports.

**[ai-forge](https://github.com/justhurky/ai-forge)** · Python, Rust, Ollama
Local multi-agent development assistant. The workspace scanner is written in Rust behind a Python
binding, and every automated change goes through a read-only diff review layer so nothing is
modified without a human looking at it.

**[LoKeD-demo](https://github.com/justhurky/LoKeD-demo)** · Python
Document-grounded administrative assistant running fully locally: it indexes documents, answers from
them, and extracts tasks and decisions from meeting notes. Published as a cleaned demo, without any
real data.

Some of my coursework and client projects are in private repositories, including an ASP.NET Core and
React event application that served around 60 concurrent users, and a car service management
backend. Happy to walk through either of them.


## Contact

- GitHub: [@justhurky](https://github.com/justhurky)
- Email: [lokid700@gmail.com](mailto:lokid700@gmail.com)
- Location: Győr, Hungary
