These are notes for the Apprenticeship Programme.
Distributed under Creative Commons Attribution Sharealike International 4.0


## Goals
* for the apprentice to be able to learn on their own
* baselining knowledge - this allows other, equally trained, people to expect knowledge of the subjects below when working with the apprentice
* for the apprentice to feel comfortable when asking questions
* allows the apprentice to formulate a plan of approaching a problem on their own - do not hand over a complete plan of actions

## General

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
* Task management (TFS and Jira)
* Build servers (TFS and Jira)

Knowledge sources

* schedule slots for reading
* Fowler's "Refactoring"
* RSS feeds [share people's feeds - see .opml files in the repo]

Noting stuff down

* introduce to 'note everything sort later' aka 'post mortems and time management for free' approach

Learn to learn

* review mistakes and sucesses every Friday
* open discussions with your peers, and not being afraid to ask stupid questions

## Tech

console

Windoze:

* cygwin + bash/zsh
* pipes, redirects
* involve grep and find for finding places in legacy code

SCM

* share configs, especially diff tool setups

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


Networking:

* ssl/tls

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
* continouous refactoring - improving your codebase rather than regressing it
* guarded coding - *always* handle any exceptions that can be thrown, and always let unhandled exceptions bubble to the top (and handle them there)
* always reproduce a bug with fully automated test first
* good naming: what it does, not how it does it
* introduction to TDD
* inner TDD loop vs outer, acceptance-tests driven TDD loop
* spikes in TDD

