These are notes for the Apprenticeship Programme.
Distributed under Creative Commons Attribution Sharealike International 4.0

## Preface

This programme intends to embed the same baseline knowledge into a new person, to avoid discovering holes in their knowledge later.

This programme needs a one-to-one pairing of apprentice with a senior developer. It must be implemented within existing team structure, already working on some project. The reason for such requirements is to present the apprentice with real-life problems. Because of the above it works best with long-term assignements, where you invest in a person and your team dynamics up front to get the work quality you need.

Recommended timeframe for covering the topics below is 3 months, however can be shortened/made longer depending on the progress of the apprentice.

## Goals
* for the apprentice to be able to learn on their own
* baselining knowledge - this allows other, equally trained, people to expect knowledge of the subjects below when working with the apprentice
* for the apprentice to feel comfortable when asking questions
* allows the apprentice to formulate a plan of approaching a problem on their own - do not hand over a complete plan of actions

## General

Before apprentice starts:  

* decide on the mentor
* make sure that everyone understands that we're investing the time now to iron out all of the issues today - this means that the whole team is taking a performance hit by accepting the apprentice, and they do want to do it anyway.
* make sure to announce when the apprentice starts to everyone involved.

Starting

* discuss experiences, come up with a plan for first week **together**

What's where  

* office supplies
*

Who's who

* show the apprentice how to locate subject-matter experts using in-house tools
* introduce people when working on particular problems [X might know about this, let us ask her !]

Office tech

* email setup
* email groups
* IM setup + testing
* VPN setup + tests
* WiFi

Company network

* intranet
* distribution lists
* Wiki
* Task management

Project infrastructure.
* Build servers

Knowledge sources

* schedule slots for reading - make Friday the day of learning
* Fowler's "Refactoring"
* RSS feeds [share people's feeds - see .opml files in the repo]

Noting stuff down

* introduce to 'note everything, sort later' aka 'post mortems and time management for free' approach

Learn to learn

* review mistakes and sucesses every Friday
* open discussions with your peers, and not being afraid to ask stupid questions

## Tech

commandline:

* bash/zsh [cygwin if Windoze]
* pipes, redirects
* when in doubt use the simpliest, most brute force tools possible, i.e. grep and find. introduce grep as a tool to check for mistakes during refactorings, etc
* involve grep and find for finding places in legacy code

SCM

* share configs, especially diff tool setups
* spend some real time explaining basics of centralized vs distributed solutions
* [good branching model reaching](http://nvie.com/posts/a-successful-git-branching-model/)
* [interactive git tutorial](http://pcottle.github.io/learnGitBranching/)
* always look at diffs before commiting

project setup -> ability to deploy

Algorithms:

* RSA
* hashes and dictionaries/hash maps

Memory management:

* mapping between native memory and JVM/CLR memory
* GC
* heap
* stack

Computer bootup process  

* [Bare metal Rust](http://www.randomhacks.net/bare-metal-rust/)
* [What happens when you type](https://github.com/alex/what-happens-when)

Networking:

* ssl/tls
* C10K problem, implement singlethreaded low level server on raw sockets

IPC

Multitasking:

* OS-level threads vs green threads
* async io
* immutability of your data and multithreading - functional programming vs object oriented

Working with code  

* codetiquette - remember that in most cases you are not the only one working on this code
* code standards - do the same monkey business your team mates do, in the same way they do it ;)
* ability to read code
* working with legacy code [freeze with tests + cut out approach]
* negate condition -> decrease indentation  
* guard clauses at the beginning  
* ifs/switch -> dictionary  
* when to refactor ?   
    * symmetry broken  
* continuous refactoring - improving your codebase rather than regressing it
* error and exception handling
    * do not use exceptions for flow control
    * talk about the difference in execution paths, how exceptions affect stack etc
    * introduce monadic error handling
    * care about what you can handle, pass all other stuff upwards
* always reproduce a bug with fully automated test first
* good naming: what it does, not how it does it
* introduction to TDD
* inner TDD loop vs outer, acceptance-tests driven TDD loop
* spikes in TDD

META

* Recommend changes to the apprenticeship programme