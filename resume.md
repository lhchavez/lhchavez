## 💼 Employment

* Google
  * Staff Software Engineer, Cloud Engineering Productivity (Oct 2018—)
    - Tech Lead of a group that is using Machine Learning to quantify risk in software development and make it useful to engineers in Cloud.
  * Software Engineer / Senior Software Engineer / Staff Software Engineer, Chrome OS (Jun 2013—Sep 2018)
    - Tech Lead of the core group that brought [Android apps to Chrome OS](https://blog.google/products/chromebooks/the-google-play-store-coming-to/).
      My team was responsible for security, stability, Inter-Process Communication, and the interactions between the core libraries of both OSs.
      Most of that work was C++, with some Java in the Android side.
    - Built part of and maintained the [containerization](https://chromium.googlesource.com/chromiumos/platform2/+/master/arc/container-bundle/README.md)
      that made it possible.
    - Presented the above in [Google I/O '16](https://www.youtube.com/watch?v=ZLYzX0G0YKQ).
    - One of the maintainers and contributors to the [minijail](https://google.github.io/minijail/) containerization library used above.
      I wrote an [optimizing cBPF compiler](https://github.com/google/minijail/blob/master/tools/README.md#compile_seccomp_policypy) that
      translates human-readable policies to BPF instructions used for seccomp-bpf syscall filtering.
      Most of that work is in C, except the compiler which is in Python.
* Microsoft
  * Software Engineer, Bing Core Ranking Platform (Aug 2011—Jun 2013)
    - Part of the group that built an optimizing compiler for a non-Turing-complete domain-specific language that extracted features
      used in the Machine Learning models in Bing's ranking algorithm.
  * Software Engineer Intern, Online Commerce Platform (Summer 2010)
    - Active Directory replication team
  * Software Engineer Intern, Online Commerce Platform (Summer 2009)
    - Active Directory replication team
  * Software Engineer Intern, Online Commerce Platform (Summer 2008)
    - Active Directory / PowerShell experience team
  
## 🎓 Education

* Stanford University (Jun 2013—May 2014)
  * Masters in Computer Science (did not graduate).
* Instituto Tecnológico y de Estudios Superiores de Monterrey, Campus Querétaro (Aug 2007—May 2011)
  * Bachelor of Science in Computer Systems Engineering
  * ACM ICPC World Finalist 2010
  * 2008-2009 Microsoft Technical Scholarship recipient
  * Winner of several national ACM ICPC-style programming contests
  
## 💚 Community Service

* Co-founder and board member of [omegaUp, Inc.](https://omegaup.org), a 501(c)(3) non-profit organization that is increasing the number of
  talented software engineers in Latin America.
  * CTO of [omegaUp](https://omegaup.com), a free online programming contest platform that is currently being used to teach algorithms in
    Mexico (this also uses minijail for its containerization / sandboxing).
* Some GitHub repos I maintain:
  * [omegaup/omegaup](https://github.com/omegaup/omegaup) - See above
  * [libgit2/git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.
  * [omegaup/gitserver](https://github.com/omegaup/gitserver) - A git server for storing problem data for omegaUp
  * [lhchavez/postmortem](https://github.com/lhchavez/postmortem) - A tiny frontend for GDB that displays the stack and Control-Flow graph of the disassembled core dump.
    Created to debug hard-to-reproduce crashes that were triggered by Undefined Behavior.
* Some GitHub repos I contribute to:
  * [libgit2/libgit2](https://github.com/libgit2/libgit2) added initial support for Sanitizers, making the library not leak, not have data races, not have deadlocks,
    not incur in Undefined Behavior, add support for multi-pack-index.
  * [vimeo/psalm](https://github.com/vimeo/psalm) [a few random fixes](https://github.com/vimeo/psalm/pulls?q=+is%3Apr+author%3Alhchavez+).
  
## ✒️ Publications

* [omegaUp: Cloud-Based Contest Management System and Training Platform in the Mexican Olympiad in Informatics.](https://ioinformatics.org/journal/v8_2014_169_178.pdf)
  LH CHÁVEZ, A GONZÁLEZ, J PONCE
  [Olympiads in Informatics 8, 2014](https://ioinformatics.org/page/ioi-journal-index/44#volume8).
* [libinteractive: A Better Way to Write Interactive Tasks](https://ioinformatics.org/journal/v9_2015_3_14.pdf)
  LH CHÁVEZ
  [Olympiads in Informatics 9, 2015](https://ioinformatics.org/page/ioi-journal-index/44#volume9).
  
## 🔀 Miscellaneous

* Fluent in Python, C++, Go, TypeScript, PHP, Java. Learning Rust.
* Current interests include a variety of topics in the realm of OS development, compilers/programming languages, static analysis, runtimes, and things of the sort.
