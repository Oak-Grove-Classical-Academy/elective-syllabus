# 2025/2026 Rust Programming Elective

## Course Description

This course introduces students to programming using Rust, a modern systems programming language. No prior experience is required. The first half focuses on building a strong foundation in Rust; the second half explores real-world applications and projects inspired by the Rust ecosystem.

## Goals

- Build foundational programming skills in Rust.
- Explore a variety of programming domains (CLI tools, web, data, etc.).
- Develop problem-solving and teamwork through projects.
- Ensure all students, regardless of background, can participate and succeed.

## Expectations

- Follow OGCA Code of Conduct.
- Be engaged and participate.
- Ask questions and seek help when needed.
- Support classmates, especially those new to programming.

## Grades

Pass/Fail based on attendance, participation, and effort.

## What You'll Need

- Mac, Linux, or Windows laptop (bring to class for Term 2 only)
- [VSCode](https://code.visualstudio.com/) installed
- [Rust](https://www.rust-lang.org/tools/install) and [Rustlings](https://rustlings.cool/) installed
- Access to [The Official Rust Book](https://doc.rust-lang.org/book/title-page.html)
- Git and Github account (optional, but recommended)

## Resources

### The Rust Book
[The Official Rust Book](https://doc.rust-lang.org/book/title-page.html) is the primary learning resource for Rust. Some topics below reference specific chapters to read. The book is free, comprehensive, and the gold standard for learning Rust.

### Rustlings
[Rustlings](https://rustlings.cool/) provides interactive exercises to practice Rust concepts. These are optional for Term 1 but can be used for Term 2 project work.

### Rust Playground
[Rust Playground](https://play.rust-lang.org/) allows you to write and run Rust code directly in your browser without installing anything. Perfect for experimenting with Rust without setting up the whole environment.

---

## Term 1

**Week 1 (2026-01-13):** Crash Course & Introduction
- What is programming? (simple explanation, analogy)
- What is Rust? (brief description)
- Why learn programming? (real-world applications, career paths)
- Course overview: syllabus, expectations, what to expect
- How the class will work: teaching, projects, exercises, support
- Q&A
- Set expectations: no prior experience needed, everyone can succeed
- Begin showcasing cool Rust projects: Probe, Buddy-Up, esvmd, snot, masterminder, Book Tracker

**Week 2 (2026-01-20):** Understanding AI & Modern Development Tools  
- What are Large Language Models (LLMs)? How do they work?
- How AI is changing software development
- Demo: OpenCode and AI-assisted coding tools
- Live coding: building a feature with AI assistance (demonstration only)
- Discussion: AI as a learning aid and development tool

**Week 3 (2026-01-27):** Version Control Concepts & Tools  
- What is version control? Why do programmers need it?
- Understanding change tracking as a graph: commits, branches, merges
- Whiteboard session: visualizing version control concepts
- Introduction to Git: the industry standard (brief overview)
- Introduction to Jujutsu (jj): modern version control with cleaner design
- Demo: tracking changes, creating branches, merging work
- Discussion: collaboration and code history in real-world projects

**Week 4 (2026-02-03):** Your First Rust Program & Basic Types  
- Anatomy of a Rust program: `fn main()` and program structure
- Cargo basics: creating and running projects
- Demo: Hello World line-by-line explanation (using Rust Playground)
- The `println!` macro and formatted output
- Understanding variables: mutable vs immutable (Rust Book Ch 3.1)
- Data types: integers, floats, booleans, characters (Rust Book Ch 3.2)

**Week 5 (2026-02-17):** Control Flow & Logic  
- Boolean values and logical operations (Rust Book Ch 3.2)
- if/else statements and decision making (Rust Book Ch 3.5)
- Comparison operators (==, !=, <, >, etc.)
- Combining conditions with && and ||
- Introduction to expressions vs statements (Rust's everything-is-an-expression philosophy)
- Demo: building simple decision-making programs

**Week 6 (2026-02-24):** Vectors & Loops  
- Introduction to vectors: creating and storing collections of data (Rust Book Ch 8.1)
- Creating vectors: `vec![]` macro and `Vec::new()`
- Vector indexing and bounds checking
- for loops: iterating through collections (Rust Book Ch 3.5)
- Iterator patterns: `.iter()` method and how for loops work
- while loops: repeating until a condition is met
- loop: infinite loops with break and continue
- Demo: processing lists of data with different loop types

**Week 7 (2026-03-03):** Functions, Structs & Ownership Basics  
- Writing your own functions: parameters and return values (Rust Book Ch 3.3)
- Function scope and organization
- Introduction to ownership: what happens when values move (Rust Book Ch 4.1)
- String vs &str: understanding owned vs borrowed string types
- String manipulation and formatting
- Introduction to structs: grouping related data (Rust Book Ch 5.1)
- Methods: functions that belong to structs (Rust Book Ch 5.3)
- Building a simple program that combines all concepts learned

## Term 2

**Week 8 (2026-03-10):** Structs, Methods & Error Handling
- Introduction to structs: grouping related data (Rust Book Ch 5.1)
- Methods: functions that belong to structs (Rust Book Ch 5.3)
- Introduction to enums through Option<T>: handling missing values (Rust Book Ch 6.1)
- Introduction to Result<T, E>: handling errors (Rust Book Ch 9.2)
- Pattern matching with `match` to handle Option and Result (Rust Book Ch 6.2)
- Demo: building a program with structs, methods, and error handling
- Review: what we've learned in Term 1
- Preview of Term 2 projects and expectations

For the rest of the term, Students work in **pairs** on projects of their choice, or on **Rustlings** (either in pairs or solo). Each week provides dedicated project work time with instructor support.

**Week 9 (2026-03-17):** Project Proposals & Team Formation  
- Students brainstorm and propose project ideas
- Form pairs for collaborative projects (or choose to work solo on Rustlings)
- **Project Ideas to Consider:**
  - CLI tools (calculator, todo list, file organizer, text processor)
  - Games (Snake, Tic-tac-toe, Hangman, puzzle solvers)
  - Web tools (scraper, API client, simple server)
  - Data tools (CSV analyzer, visualization, file backup)
- **Rustlings Option:** Begin with options, generics, traits (Read: §10, §10.1, §10.2)
- Finalize project proposals and get instructor approval

**Week 10 (2026-03-24):** Project Work - Getting Started  
- **Project Teams:** Begin implementation of approved projects
- Set up project repositories and development environment
- Create basic project structure and initial features
- **Rustlings Option (pairs or solo):** lifetimes, tests (Read: §10.3, §11.1)
- Project work time with instructor support

**Week 11 (2026-03-31):** Project Work - Advanced Features  
- **Project Options (work in pairs):**
  - Build a simple game (Snake, Tic-tac-toe, Hangman, etc.)
  - Create a data analysis tool for CSV files
  - Design a file backup or synchronization tool
- **Rustlings Option (pairs or solo):** iterators, smart_pointers (Read: §13.2-4, §15)
- Project work time with instructor support

**Week 12 (2026-04-07):** Project Work - Concurrency & Networking  
- **Project Options (work in pairs):**
  - Build a web scraper or API client
  - Create a simple chat application or messaging system
  - Design a download manager or file transfer tool
- **Rustlings Option (pairs or solo):** threads, macros (Read: §16.1-3, §19.5)
- Project work time with instructor support

**Week 13 (2026-04-14):** Project Work - Command-Line Tools  
- **Project Options (work in pairs):**
  - Build an advanced CLI tool using [clap](https://github.com/clap-rs/clap)
  - Create a system monitoring or automation tool
  - Design a code formatter or development utility
- **Rustlings Option (pairs or solo):** conversions, clippy
- Project work time with instructor support

**Week 14 (2026-04-21):** Project Work - Web & Data  
- **Project Options (work in pairs):**
  - Build a web server or API using [Rocket](https://rocket.rs/) or [Actix](https://actix.rs/)
  - Create a database-backed application
  - Design a data visualization or analysis tool
- **Rustlings Option (pairs or solo):** Complete remaining exercises
- Project work time with instructor support

**Week 15 (2026-04-28):** Final Project Polish  
- **All Students:** Polish and extend current projects
- Add new features, improve user interface, write documentation
- Prepare project presentations
- Project work time with instructor support

**Week 16 (2026-05-05):** Project Presentations & Wrap-Up  
- **Pair teams** present their collaborative projects
- **Rustlings students** share progress and favorite exercises
- Q&A, feedback, and next steps for continued learning  
- Treats and celebration!

---

## Notes from Student Feedback

- Go slower and explain concepts in more depth, especially for beginners.
- Dedicate time to basics and setup, including a "crash course" day.
- Encourage questions and provide extra support for those who miss early classes.
- Integrate more Rust syntax and language fundamentals alongside projects.
- Use practical exercises and real-world examples.
- Provide resources for catching up if absent.
