# Rust-Learning-Archive
Rust Materials for new comers
![rustBanner](./img/rustacean-banner.png)


## If you are new to Rust, please follow these tutorials

* [Rust By Example](https://doc.rust-lang.org/rust-by-example)
* [Rust Book](https://doc.rust-lang.org/book/)

## TABLE OF CONTENTS

* [Rust Books](./RustBooks/README.md)
* [Rust Links](./RustLinks/README.md)
* [Rust Security](./RustSecurity/README.md)


# rust-learning [Credits](https://github.com/ctjhoa/rust-learning)

A bunch of links to blog posts, articles, videos, etc for learning Rust. Feel free to submit a pull request if you have some links/resources to add. Also, I try to verify that the articles below have some real content (i.e. they aren't 2 paragraph long blog posts with little information) to ensure I'm not listing "fluff" pieces. If you have an idea for a better way to organize these links, please let me know.

## Introduction

*Do you want to be convinced that Rust is worth learning?* Let us show you the [True Nature of the Force](https://brson.github.io/fireflowers/).

The main documentation is always the best beginning, so if you haven't read it yet, start by reading the [Rust docs](https://www.rust-lang.org/en-US/documentation.html). You can also have the ebook versions of the doc [here](http://killercup.github.io/trpl-ebook/) and [here](https://github.com/lise-henry/books/).

### Tag meanings

* :star: Something made by a rust team member.
* :end: Concepts are still useful but code could not compile.
* :soon: Work In Progress.

## Table of Contents

* [Books](#books)
* [Videos](#videos)
  * [Playlists](#playlists)
  * [Presentations](#presentations)
* [Podcasts](#podcasts)
* [Rust in practice](#rust-in-practice)
* [Best Practices/Style Guides](#best-practicesstyle-guides)
* [Cheat sheets](#cheat-sheets)
* [Rust internals](#rust-internals)
* [Compilation](#compilation)
* [FFI](#ffi)
* [CI / Testing](#ci--testing)
* [Debug / Profiling](#debug--profiling)
* [Are we ... yet?](#are-we--yet)
* [Applications / Libraries / Tools](#applications--libraries--tools)
* [Language stuff](#language-stuff)
  * [Async](#async)
  * [Closures](#closures)
  * [Documentation](#documentation)
  * [Enums](#enums)
  * [Iterators](#iterators)
  * [Lifetime](#lifetime)
  * [MIR](#mir)
  * [Modules](#modules)
  * [Option & Result](#option--result)
  * [Ownership / Concurrency](#ownership--concurrency)
  * [Privacy](#privacy)
  * [Strings](#strings)
  * [Syntax extensions](#syntax-extensions)
  * [Traits](#traits)
  * [Unsafe](#unsafe)
* [Playground](#playground)
* [People](#people)
  * [Fearless Rust Bloggers](#fearless-rust-bloggers)
* [Tutorials & Workshop Materials](#tutorials--workshop-materials)
* [Similar projects](#similar-projects)

## Books

* :star: [The Rust Programming Language](https://doc.rust-lang.org/stable/book/) - [repo](https://github.com/rust-lang/book)
* :star: [The Rust Reference](https://doc.rust-lang.org/stable/reference/) - [repo](https://github.com/rust-lang/reference)
* :star: [The Rustonomicon - The Dark Arts of Advanced and Unsafe Rust Programming](https://doc.rust-lang.org/stable/nomicon/) - [repo](https://github.com/rust-lang/nomicon)
* :star: [The Unstable Book](https://doc.rust-lang.org/stable/unstable-book/) - [repo](https://github.com/rust-lang/rust/tree/master/src/doc/unstable-book)
* :star: [The Rust Edition Guide](https://doc.rust-lang.org/edition-guide/) - [repo](https://github.com/rust-lang/edition-guide)
* :star: [The Rust Async Book](https://rust-lang.github.io/async-book/) - [repo](https://github.com/rust-lang/async-book)
* :star: [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) - [repo](https://github.com/rust-lang-nursery/rust-cookbook)
* :star: [Why Rust?](https://www.oreilly.com/content/why-rust/) - [Jim Blandy][]
* :star: [The Embedded Rust Book](https://rust-embedded.github.io/book/intro/index.html) - [repo](https://github.com/rust-embedded/book) - Rust Embedded WG
* [Rust-101](https://www.ralfj.de/projects/rust-101/main.html) - Ralf Jung
* [Rust Essentials](https://www.packtpub.com/application-development/rust-essentials-second-edition) -  Ivo Balbaert
* [Programming Rust](http://shop.oreilly.com/product/0636920040385.do) - [Jim Blandy][], Jason Orendorff
* [Mastering Rust - Second Edition](https://www.packtpub.com/application-development/mastering-rust-second-edition) - Rahul Sharma & Vesa Kaihlavirta
* :soon: [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - [repo](https://github.com/natemara/refactoring-to-rust) - Nate Mara
* :star: [Rust Anthology](https://github.com/brson/rust-anthology) - [Brian Anderson][]
* :soon: [Rust in Action](https://www.manning.com/books/rust-in-action) - [repo](https://github.com/rust-in-action/code) - [Tim McNamara][]
* :soon: [Zero To Production In Rust](https://zero2prod.com) - [repo](https://github.com/LukeMathWalker/zero-to-production) - [Luca Palmieri][]
* [Network Programming in Rust](https://www.packtpub.com/application-development/network-programming-rust) - Abhishek Chanda
* [Learning Rust](https://www.packtpub.com/application-development/learning-rust) -  Paul Johnson, Vesa Kaihlavirta
* [Rust Cookbook](https://www.packtpub.com/application-development/rust-cookbook) -  Vigneshwer Dhinakaran
* [Learning Rust](https://learning-rust.github.io/) - [Dumindu Madunuwan][]
* [A Gentle Introduction To Rust](http://stevedonovan.github.io/rust-gentle-intro/readme.html) - [Steve Donovan][]
* [Step Ahead with Rust](https://www.amazon.com/dp/0999361805/) - Jonathan Creekmore
* :star: [Rust Programming By Example](https://www.amazon.com/dp/1788390636) - Guillaume Gomez and Antoni Boucher
* [Beginning Rust - From Novice to Professional](https://www.apress.com/us/book/9781484234679) - Carlo Milanesi
* [Hands-On Concurrency with Rust](https://www.amazon.com/dp/1788399978) - Brian Troutwine
* [Hands-On Functional Programming in Rust](https://www.amazon.com/dp/1788839358) - Andrew Johnson
* [Hands-On Rust Effective Learning through 2D Game Development and Play](https://pragprog.com/titles/hwrust/hands-on-rust) - Herbert Wolverson
* [Hands-On Microservices with Rust](https://www.packtpub.com/web-development/hands-microservices-rust) - Denis Kolodin
* [Hands-On Data Structures and Algorithms with Rust](https://www.packtpub.com/application-development/hands-data-structures-and-algorithms-rust) - Claus Matzinger
* [Rust Standard Library Cookbook](https://www.amazon.com/Rust-Standard-Library-Cookbook-leverage/dp/1788623924) - Daniel Durante, Jan Nils Ferner
* [Rust Quick Start Guide](https://www.amazon.com/Rust-Quick-Start-Guide-programming/dp/1789616700) - Daniel Arbuckle
* [Rust High Performance](https://www.amazon.com/Rust-High-Performance-performance-applications/dp/178839948X) - Iban Eguia Moraza
* [Programming WebAssembly with Rust](https://pragprog.com/book/khrust/programming-webassembly-with-rust) - Kevin Hoffman
* [Hands-On Microservices with Rust 2018: How To Build Scalable and Reliable RESTful Microservices](https://www.amazon.co.uk/Hands-Microservices-Rust-2018-Scalable/dp/1789342759/ref=sr_1_6?s=books&ie=UTF8&qid=1545340800&sr=1-6&keywords=rust) - Denis Kolodin
* [Hands-On Data Structures and Algorithms with Rust](https://www.packtpub.com/application-development/hands-data-structures-and-algorithms-rust) - Claus Matzinger
* [The Complete Rust Programming Reference Guide: Design, develop, and deploy effective software systems using the advanced constructs of Rust](https://www.amazon.com/Complete-Rust-Programming-Reference-Guide/dp/1838828109) - - Vesa Kaihlavirta, Rahul Sharma, Claus Matzinger
* [Easy Rust](https://github.com/Dhghomon/easy_rust) - David MacLeod
* :soon: [Rust Web Development](https://www.manning.com/books/rust-web-development) - [repo](https://github.com/Rust-Web-Development/code) - Bastian Gruber
* [The Little Book of Rust Books](https://lborb.github.io/book/) - [repo](https://github.com/lborb/book)
* [Rust Servers, Services, and Apps](https://www.manning.com/books/rust-servers-services-and-apps) - Prabhu Eshwarla
* [Code Like a Pro in Rust](https://www.manning.com/books/code-like-a-pro-in-rust) - Brenden Matthews
* [Rust for Rustaceans](https://nostarch.com/rust-rustaceans) - Jon Gjengset
* [Rust From the Ground Up](https://rftgu.rs/) - Matthew Provost

## Videos

### Playlists

* :star: [Rust and the Future of Systems Programming](https://www.youtube.com/playlist?list=PLo3w8EB99pqJ74XIGe72c9hBZWz9Y16cY) - Mozilla
* [RustFest Zürich 2017](https://www.youtube.com/watch?v=jywiVWKm1TI&list=PL85XCvVPmGQj9mqbJizw-zi-EhcpS5jTP)
* [J M Archer Tutorials](https://www.youtube.com/playlist?list=PLTOeCUgrkpMNEHx6j0vCH0cuyAIVZadnc) - J M Archer
* [ABitWiseGuy Tutorials](https://www.youtube.com/watch?v=y-ks-_VDkiA&list=PL0Fqs05rod8D80WKBCeT326CT8vcAm_N9) - ABitWiseGuy
* [dcode Tutorials](https://www.youtube.com/watch?v=vOMJlQ5B-M0&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL) - dcode
* [Tensor Programming Tutorials](https://www.youtube.com/watch?v=EYqceb2AnkU&list=PLJbE2Yu2zumDF6BX6_RdPisRVHgzV02NW) - Tensor Programming
* [Hello Rust!](https://www.youtube.com/channel/UCZ_EWaQZCZuGGfnuqUoHujw) - Matthias Endler
* [YouCodeThings](https://www.youtube.com/channel/UC0yCXVwW6FdDQGYA-3OWXxw/) - Andrew Jakubowicz
* :star: :soon: [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion) - Video course by [Carol Nichols][] and Jake Goulding
* [Learn Rust in 7 Days](https://www.packtpub.com/application-development/learn-rust-7-days-video) - Matthew Stoodley
* [Rust Tutorial](https://www.youtube.com/watch?v=Az3jBd4xdF4&list=PLLqEtX6ql2EyPAZ1M2_C0GgVd4A-_L4_5) - Doug Milford
* [Rust](https://www.youtube.com/watch?v=bR4nGWmfzTk&list=PLVhhUNGAUIQScqB26DdUq4n1Y2n3auM7X) - Crazcalm's Tech Stack
* [Rust Advent of Code 2019](https://www.youtube.com/playlist?list=PLQXBtq4j4Ozkx3r4eoMstdkkOG98qpBfg) - Brian Myers
* [The Rust Programming Language | Tutorials](https://www.youtube.com/playlist?list=PLK_g1a_cAfaaAO6io1Tluy7EZXhAAK1lC) - danlogs
* [Ryan Levick's Rust Stream](https://www.youtube.com/channel/UCpeX4D-ArTrsqvhLapAHprQ/videos) - Ryan Levick
* [Crust of Rust](https://www.youtube.com/playlist?list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa) - Jon Gjengset
* [ULTIMATE Rust Lang Tutorial!](https://www.youtube.com/watch?v=OX9HJsJUDxA&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8) - Let's Get Rusty
* [Overview of the Rust Programming Language](https://www.youtube.com/watch?v=gesNaLkUJeA&list=PLP2yfE2-FXdQmXLvrQ5QN64enbF_KCYQW) - [Jonathan Turner][]
* [Manning Publications Rust channel](https://www.youtube.com/c/ManningPublications/search?query=rust) - Manning Publications
* [Introduction to Programming with Rust](https://www.youtube.com/playlist?list=PLbtjxiXev6lpd331MW2dB7UgSIovgv169) - Rhymu's Videos

### Presentations

* 2021-06-25 - [How to learn Rust](https://youtu.be/sDtQaO5_SOw) - [Tim McNamara][]
* 2021-06-01 - [A Firehose of Rust, for busy people who know some C++](https://www.youtube.com/watch?v=IPmRDS0OSxM) - Jack O'Connor
* 2020-09-21 - [live@Manning Rust Conference](https://www.youtube.com/watch?v=9nINNurVqz8) - [Carol Nichols][], [Tim McNamara][], Maciej Hirsz, Olivia Ifrim, Nell Shamrell-Harrington, Pierre Krieger, Richard Walters, Chris Griffing, Lachezar Lechev, Michael Hausenblas
* 2017-06-20 - :star: [Rust: Putting Ownership to Use](https://www.youtube.com/watch?v=wXoY91w4Agk) - [Niko Matsakis][]
* 2017-01-20 - [Rust 101](https://www.youtube.com/watch?v=FMqydRampuo) - E. Dunham
* 2016-09-28 - [Mozilla's Rust and why we love it](https://www.youtube.com/watch?v=LuNhkRxP2E4) - Cambridge Consultants
* 2016-09-25 - :star: [into_rust() - Screencasts for learning rust!](http://intorust.com/) - [Niko Matsakis][]
* 2016-08-28 - :star: [Rust: Safe and Scalable Systems Programming](https://www.youtube.com/watch?v=GbWECt0M3CI) - [Alex Crichton][]
* 2016-06-21 - :star: [The History of Rust](https://www.youtube.com/watch?v=79PSagCD_AY) - [Steve Klabnik][]
* 2015-08-01 - :star: [RustCamp 2015](https://www.youtube.com/watch?v=0qIAk5sTwEo&list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t)
* 2015-06-22 - [LambdaConf 2015 - In Rust We Trust](https://www.youtube.com/watch?v=-dxqbhLIgdM) - Alex Burkhart
* 2015-06-13 - :star: [What Is Rust?](http://www.infoq.com/presentations/rust-gc) - [Yehuda Katz][]
* 2015-04-11 - [My Python's a little Rust-y](https://www.youtube.com/watch?v=3CwJ0MH-4MA) - [Dan Callahan][]
* 2015-03-12 - :star: [Stanford Seminar](https://www.youtube.com/watch?v=O5vzLKg7y-k) - [Aaron Turon][]

## Podcasts

* [Moves and Borrowing In Rust With Jim Blandy](https://corecursive.com/016-moves-and-borrowing-in-rust-with-jim-blandy/) - Adam Bell
* [New Rustacean](http://www.newrustacean.com) - [Chris Krycho][]
* [The Request for Explanation Podcast: A weekly discussion of Rust RFCs](https://request-for-explanation.github.io/podcast/) - [Manish Goregaokar][]
* [Rust And Bitter C++ Developers With Jim Blandy](https://corecursive.com/013-rust-and-bitter-c-developers-with-jim-blandy/) - Adam Bell
* [AreWePodcastYet](https://soundcloud.com/arewepodcastyet)
* [Rustacean Station](https://rustacean-station.org/)

## Rust in practice

* :star: [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/) - [Jorge Aparicio][] and [Steve Klabnik][] - [repo](https://github.com/rust-lang/rust-by-example)
* [rosettacode](https://github.com/Hoverbear/rust-rosetta) - [Andrew Hobden][]
* [Why your first FizzBuzz implementation may not work](http://chrismorgan.info/blog/rust-fizzbuzz.html) - [Chris Morgan][]
* :star: [An annotation of the Rust standard library](https://github.com/brson/annotated-std-rs) - [Brian Anderson][]
* [ProjectEulerRust](https://github.com/gifnksm/ProjectEulerRust) - gifnksm
* [Advent of Code](https://github.com/LD250/adventofcode_rust) - Denys Levchenko
* [Rust in Detail: Writing Scalable Chat Service from Scratch](https://nbaksalyar.github.io/) - Nikita Baksalyar
* :star: [rustlings: small rust exercises](https://github.com/carols10cents/rustlings) - [Carol Nichols][]
* [Learning Rust With Entirely Too Many Linked Lists](http://cglab.ca/~abeinges/blah/too-many-lists/book/) - [Alexis Beingessner][]
* :star: [Let's build a browser engine!](http://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html) - Matt Brubeck
* [Understanding Over Guesswork](http://hoverbear.org/2015/09/12/understand-over-guesswork/) - [Andrew Hobden][]
* [Writing an OS in Rust 1st edition](http://os.phil-opp.com/) [2nd edition](https://os.phil-opp.com/second-edition/) - Philipp Oppermann
* [Creating Nintendo 64 emulator from scratch in Rust!](https://www.youtube.com/playlist?list=PL-sXmdrqqYYcznDg4xwAJWQgNL2gRray2) - Jake Taylor
* [The Many Kinds of Code Reuse in Rust](http://cglab.ca/~abeinges/blah/rust-reuse-and-recycle/) - [Alexis Beingessner][]
* [Make a Lisp](https://github.com/kanaka/mal) - Joel Martin
* :star: [Modeling Graphs in Rust Using Vector Indices](http://smallcultfollowing.com/babysteps/blog/2015/04/06/modeling-graphs-in-rust-using-vector-indices/) - [Niko Matsakis][]
* [24 days of Rust series](https://siciarz.net/tag/24%20days%20of%20rust/) - Zbigniew Siciarz
* :star: [Rust Cookbook](https://github.com/brson/rust-cookbook)
* :star: [Rust and CSV Parsing](http://blog.burntsushi.net/csv/) - [Andrew Gallant][]
* [Algorithm Cookbook in Rust](https://github.com/EbTech/rust-algorithms) - Aram Ebtekar
* :star: [stdx - The missing batteries of Rust](https://github.com/brson/stdx) - [Brian Anderson][]
* [Rust - exercism.org](https://exercism.org/tracks/rust)
* [Building a DNS server in Rust](https://github.com/EmilHernvall/dnsguide) - Emil Hernvall
* [Rust Crash Course](https://www.snoyman.com/feed/rust-crash-course) - Michael Snoyman
* [Web browser from scratch in Rust](https://joshondesign.com/tags/browser) - Josh Marinacci
* [Tour of Rust](https://tourofrust.com/) - Richard Anaya
* [PNGme: An Intermediate Rust Project](https://picklenerd.github.io/pngme_book/) - picklenerd
* [Create Your Own Programming Language with Rust](https://createlang.rs/) - Ehsan M. Kermani
* :star: [Command Line Applications in Rust](https://rust-cli.github.io/book/) - Rust CLI working
* [Writing a file system from scratch in Rust](https://blog.carlosgaldino.com/writing-a-file-system-from-scratch-in-rust.html) - Carlos Galdino
* [Hecto: Build your own text editor in Rust](https://www.philippflenker.com/hecto/) - Philipp Flenker
* [Rust sokoban](https://sokoban.iolivia.me/) - Olivia Ifrim
* [Rust Gym](https://github.com/warycat/rustgym) - Yinchu Xia
* :star: [Rust Quiz](https://dtolnay.github.io/rust-quiz) - David Tolnay

## Best Practices/Style Guides

* :star: [Rust Design Patterns](https://github.com/nrc/patterns) - [Nick Cameron][]
* :star: [Error Handling in Rust](http://blog.burntsushi.net/rust-error-handling/) - [Andrew Gallant][]
* :star: [Rust API guidelines](https://github.com/rust-lang/rust-api-guidelines) - [Brian Anderson][]
* [Reading Rust Function Signatures](http://hoverbear.org/2015/07/10/reading-rust-function-signatures/) - [Andrew Hobden][]
* [Good Practices for Writing Rust Libraries](https://pascalhertleif.de/artikel/good-practices-for-writing-rust-libraries/) - [Pascal Hertleif][]
* [Rustic Bits](https://llogiq.github.io/2016/02/11/rustic.html) - [Llogiq][]
* [Pretty State Machine Patterns in Rust](https://hoverbear.org/2016/10/12/rust-state-machine-pattern/) - [Andrew Hobden][]
* [Elegant Library APIs in Rust](https://scribbles.pascalhertleif.de/elegant-apis-in-rust.html) - [Pascal Hertleif][]
* [Rust Performance Pitfalls](https://llogiq.github.io/2017/06/01/perf-pitfalls.html) - [Llogiq][]
* [How to write CRaP Rust code](https://blog.logrocket.com/how-to-write-crap-rust-code/) - [Llogiq][]
* [The Rust Performance Book](https://github.com/nnethercote/perf-book) - Nicholas Nethercote

## Cheat sheets

* :star: [Syntax Index](https://doc.rust-lang.org/book/syntax-index.html)
* [The Periodic Table of Rust Types](http://cosmic.mearie.org/2014/01/periodic-table-of-rust-types/) - Kang Seonghoon
* [Rust Iterator Cheat Sheet](https://danielkeep.github.io/itercheat_baked.html) - [Daniel Keep][]
* [Rust String Conversions Cheat Sheet](https://docs.google.com/spreadsheets/d/19vSPL6z2d50JlyzwxariaYD6EU2QQUQqIDOGbiGQC7Y/pubhtml?gid=0&single=true) - GavinB
* [Rustic Symmetries](https://github.com/kmcallister/rustic-symmetries/blob/master/README.md#rustic-symmetries) - kmc
* [Rust Container Cheat Sheet](https://docs.google.com/presentation/d/1q-c7UAyrUlM-eZyTo1pd8SZ0qwA_wYxmPZVOQkoDmH4/edit?usp=sharing) - Raph Levien
* [Graphical depiction of ownership and borrowing in Rust](https://rufflewind.com/img/rust-move-copy-borrow.png) - Phil Ruffwind
* [Lifetime Reference](https://www.charlesetc.com/lifetime-reference/) - Charles
* [Phaiax's Rust Cheatsheet](http://phaiax.github.io/rust-cheatsheet/) - Phaiax
* [Rust Language Cheat Sheet](https://cheats.rs/) - Ralf Biedert
* [Rust cheat sheet (beginner-oriented)](https://www.breakdown-notes.com/make/load/rust_cs_canvas/true)
* [A type-based Rust cheatsheet](https://upsuper.github.io/rust-cheatsheet/) - Xidorn Quan

## Rust internals

* :star: [Rust RFCs](https://github.com/rust-lang/rfcs) and [Accepted RFCs](https://rust-lang.github.io/rfcs/)
* :star: [Rust Forge](https://forge.rust-lang.org/)
* :star: [Internals Forum](https://internals.rust-lang.org/)

## Compilation

* [rust-cross, Everything you need to know about cross compiling Rust programs!](https://github.com/japaric/rust-cross) - [Jorge Aparicio][]
* [How to cross compile Rust from OS X to FreeBSD](https://github.com/yohanesu75/crossrust) - yohanesu75
* [Cross Compiling for Raspberry Pi](https://github.com/Ogeon/rust-on-raspberry-pi) - Ogeon
* :star: [Taking Rust everywhere with rustup](http://blog.rust-lang.org/2016/05/13/rustup.html) - [Brian Anderson][]
* [Why is a Rust executable large?](https://lifthrasiir.github.io/rustlog/why-is-a-rust-executable-large.html) - Kang Seonghoon
* [Rust your ARM microcontroller!](http://blog.japaric.io/quickstart/) - [Jorge Aparicio][]
* [Cross-compiling Rust for the Raspberry Pi on macOS](https://akappel.github.io/2017/11/07/rpi-crosstool.html) - Adrian Kappel
* [rust-on-mobile](https://github.com/mtak-/rust-on-mobile) - mtak-
* [Compile Time Feature Flags in Rust](https://www.worthe-it.co.za/programming/2018/11/18/compile-time-feature-flags-in-rust.html) - Justin Worthe
* [Rust on iOS](https://medium.com/visly/rust-on-ios-39f799b3c1dd) - Emil Sjölander

## FFI

* 2017-11-22 - [Writing fast and safe native Node.js modules with Rust](https://blog.risingstack.com/node-js-native-modules-with-rust/) - Peter Czibik
* 2017-09-21 - [Building and Deploying a Rust library on Android](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-21-rust-on-android.html) - Emily Toop
* 2017-09-06 - [Building and Deploying a Rust library on iOS](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-06-rust-on-ios.html) - Emily Toop
* 2020-09-08 - [I C and .so does Rust](https://prateeknischal.github.io/posts/i-c-and-so-does-rust/) - prateeknischal
* [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/?updated=2015-11-08) - Jake Goulding
* [The Rust FFI Guide - using unsafe for fun and profit](https://michael-f-bryan.github.io/rust-ffi-guide/) - Michael-F-Brya

## CI / Testing

* [Helping Travis catch the rustc train part 1](https://huonw.github.io/blog/2015/04/helping-travis-catch-the-rustc-train/) | [part 2](https://huonw.github.io/blog/2015/05/travis-on-the-train-part-2/) - [Huon Wilson][]
* [Rust, Travis, and Github Pages](http://hoverbear.org/2015/03/07/rust-travis-github-pages/) - [Andrew Hobden][]
* [Shave Some Time From Your Travis Builds](https://llogiq.github.io/2016/07/05/travis.html) - [Llogiq][]
* [How to collect test coverages for a rust project](https://users.rust-lang.org/t/tutorial-how-to-collect-test-coverages-for-rust-project/650) - lifthrasiir
* [Rust Code Coverage Guide: kcov + Travis CI + Codecov / Coveralls](http://sunjay.ca/2016/07/25/rust-code-coverage) - Sunjay Varma
* [Rust Performance Testing on Travis CI](https://beachape.com/blog/2016/11/02/rust-performance-testing-on-travis-ci/) - Lloyd
* [Ensuring Beautiful Commits with rustfmt and Travis-CI](http://kneit.in/2016/11/26/rustfmt-in-travisci.html) - Kyle Kneitinger
* [Great Rust CI](https://dev.to/cad97/great-rust-ci-1fk6) - Christopher Durham
* [Rust Fuzz Book](https://rust-fuzz.github.io/book/)

## Debug / Profiling

* [Debugging a segfault in my Rust program](https://jvns.ca/blog/2017/12/23/segfault-debugging/) - Julia Evans
* [Compiler Explorer - See Rust code as assembly](https://rust.godbolt.org/)
* [Profiling Rust applications on Linux](http://llogiq.github.io/2015/07/15/profiling.html) - [Llogiq][]

## Are we ... yet?

* [Are we web yet?](http://www.arewewebyet.org/)
* [Are we (I)DE yet?](https://areweideyet.com/)
* [Are we game yet?](http://arewegameyet.com/)
* [Are we learning yet?](http://www.arewelearningyet.com/)
* [Are we async yet?](https://areweasyncyet.rs/)
* [Not-Yet-Awesome Rust](https://github.com/ErichDonGubler/not-yet-awesome-rust)
* [Are we GUI yet?](http://areweguiyet.com/)


## Applications / Libraries / Tools

See repos [kud1ing/awesome-rust](https://github.com/kud1ing/awesome-rust) & [awesomo
/rust](https://github.com/lk-geimfari/awesomo/blob/master/languages/RUST.md)

## Language stuff

Can I use feature X? [caniuse.rs - Rust feature search](https://caniuse.rs/)

### Async

* [Futures Explained in 200 Lines of Rust](https://cfsamson.github.io/books-futures-explained/) - Carl Fredrik Samson

### Closures

* [Finding Closure in Rust](https://huonw.github.io/blog/2015/05/finding-closure-in-rust/) - [Huon Wilson][]
* [Defaulting to Thread-Safety: Closures and Concurrency](https://huonw.github.io/blog/2015/05/defaulting-to-thread-safety/) - [Huon Wilson][]
* [How to pass a closure into a trait object](http://camjackson.net/post/rust-lang-how-to-pass-a-closure-into-a-trait-object) - Cam Jackson
* [Practical differences between Rust closures and functions](https://ricardomartins.cc/2015/10/12/practical_differences_between_rust_closures_and_functions) - Ricardo Martins
* :star: [How Rust Achieves Thread Safety](https://manishearth.github.io/blog/2015/05/30/how-rust-achieves-thread-safety/) - [Manish Goregaokar][]
* [Understanding Closures in Rust](https://medium.com/swlh/understanding-closures-in-rust-21f286ed1759) - [Steve Donovan][]
* [Why Rust Closures are (Somewhat) Hard](https://stevedonovan.github.io/rustifications/2018/08/18/rust-closures-are-hard.html) - Andrew Pritchard

### Documentation

* :star: [Writing Documentation in Rust](https://www.facility9.com/2016/05/10/writing-documentation-in-rust/) - [Jeremiah Peschka][]
* [Keeping Rust projects' README.md code examples up-to-date](https://blog.guillaume-gomez.fr/articles/2019-04-13+Keeping+Rust+projects%27+README.md+code+examples+up-to-date) - Guillaume Gomez
* [Guide on how to write documentation for a Rust crate](https://blog.guillaume-gomez.fr/articles/2020-03-11+Guide+on+how+to+write+documentation+for+a+Rust+crate) - Guillaume Gomez

### Enums

* :star: [Virtual Structs part 1](http://smallcultfollowing.com/babysteps/blog/2015/05/05/where-rusts-enum-shines/) | [part 2](http://smallcultfollowing.com/babysteps/blog/2015/05/29/classes-strike-back/) | [part 3](http://smallcultfollowing.com/babysteps/blog/2015/08/20/virtual-structs-part-3-bringing-enums-and-structs-together/) - [Niko Matsakis][]

### Errors

* :star: [Error Handling in Rust](https://blog.burntsushi.net/rust-error-handling/) - [Andrew Gallant][]
* [Beginner's guide to Error Handling in Rust](http://www.sheshbabu.com/posts/rust-error-handling/) - Sheshbabu Chinnakonda
* [Rust error handling](https://www.unwoundstack.com/blog/rust-error-handling.html) - sp1ff
* [Rust: Structuring and handling errors in 2020](https://nick.groenen.me/posts/rust-error-handling/) - Nick Groenen
* [Wrapping errors in Rust](https://edgarluque.com/blog/wrapping-errors-in-rust/) - Edgar Luque

### Iterators

* [A Journey into Iterators](http://hoverbear.org/2015/05/02/a-journey-into-iterators/) - [Andrew Hobden][]
* [Effectively Using Iterators In Rust](http://hermanradtke.com/2015/06/22/effectively-using-iterators-in-rust.html) - [Herman J. Radtke III][]
* [for loops in Rust](http://xion.io/post/code/rust-for-loop.html) - Karol Kuczmarski
* [Iteration patterns for Result & Option](http://xion.io/post/code/rust-iter-patterns.html) - Karol Kuczmarski
* [Little tour of multiple iterators implementation in Rust](https://blog.guillaume-gomez.fr/articles/2017-03-09+Little+tour+of+multiple+iterators+implementation+in+Rust) - Guillaume Gomez
* [rust-iterators](https://github.com/rustomax/rust-iterators/) - Max Skybin

### Lifetime

* :star: [Where Rust Really Shines](https://manishearth.github.io/blog/2015/05/03/where-rust-really-shines/) - [Manish Goregaokar][]
* [Understanding Lifetime in Rust part 1](https://mobiarch.wordpress.com/2015/06/29/understanding-lifetime-in-rust-part-i/) | [part 2](https://mobiarch.wordpress.com/2015/07/08/understanding-lifetime-in-rust-part-ii-3/) - Bibhas Bhattacharya
* [Rust Lifetimes](https://www.charlesetc.com/rust-lifetimes/) - Charles
* [The Power of Lifetimes](http://pling.jondgoodwin.com/post/lifetimes/) - Jonathan Goodwin
* [Understanding Lifetimes](https://rniczh.github.io/blog/lifetimes-intro/) - Hong-Sheng ‘Rnic‘ Zheng
* [Understanding Rust Lifetimes](https://medium.com/nearprotocol/understanding-rust-lifetimes-e813bcd405fa) - Maksym Zavershynskyi
* [Common Rust Lifetime Misconceptions](https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md) - kirill

### Macros

* [A Practical Intro to Macros in Rust 1.0](https://danielkeep.github.io/practical-intro-to-macros.html) - [Daniel Keep][]
* [The Little Book of Rust Macros](https://veykril.github.io/tlborm/) - Lukas Wirth
* :star: [Macros in Rust part 1](http://www.ncameron.org/blog/macros-in-rust-pt1/) | [part 2](http://www.ncameron.org/blog/macros-in-rust-pt2/) | [part 3](http://ncameron.org/blog/macros-in-rust-pt3/) | [part 4](http://ncameron.org/blog/macros-in-rust-pt4/) - [Nick Cameron][]
* [How do I use the Standard Library Macros in Rust?](https://blog.mgattozzi.dev/how-do-i-std-macros) - [Michael Gattozzi][]
* [Writing complex macros in Rust: Reverse Polish Notation](https://rreverser.com/writing-complex-macros-in-rust/) - Ingvar Stepanyan
* :star: [Procedural Macros in Rust 2018](https://blog.rust-lang.org/2018/12/21/Procedural-Macros-in-Rust-2018.html) - [Alex Crichton][]
* [Creating Macros in Rust](https://hub.packtpub.com/creating-macros-in-rust-tutorial/) - Aaron Lazar

### MIR

* :star: [Introducing MIR](http://blog.rust-lang.org/2016/04/19/MIR.html) - [Niko Matsakis][]

### Modules

* [Rust Module Essentials ](https://dev.to/hertz4/rust-module-essentials-12oi) - Sam Pagenkopf
* [How I Organize Large Rust Programs](https://rodarmor.com/blog/tour-de-just/) - Casey Rodarmor
* [Clear explanation of Rust’s module system](http://www.sheshbabu.com/posts/rust-module-system/) - Sheshbabu Chinnakonda

### Option & Result

* [Option Type part 1](http://blog.8thlight.com/dave-torre/2015/03/11/the-option-type.html) | [part 2](http://blog.8thlight.com/uku-taht/2015/04/29/using-the-option-type-effectively.html) - 8thlight
* :end: [Option Monads in Rust](http://hoverbear.org/2014/08/12/option-monads-in-rust/) - [Andrew Hobden][]
* [Russian Dolls and clean Rust code](https://blog.mgattozzi.dev/russian-dolls) - [Michael Gattozzi][]

### Ownership / Concurrency

* :star: [Fearless Concurrency with Rust](http://blog.rust-lang.org/2015/04/10/Fearless-Concurrency.html) - [Aaron Turon][]
* [Rust ownership, the hard way](http://chrismorgan.info/blog/rust-ownership-the-hard-way.html) - [Chris Morgan][]
* :star: [An alternative introduction to Rust](http://words.steveklabnik.com/a-new-introduction-to-rust) - [Steve Klabnik][]
* :star: [The Problem With Single-threaded Shared Mutability](https://manishearth.github.io/blog/2015/05/17/the-problem-with-shared-mutability/) - [Manish Goregaokar][]
* :star: [Wrapper Types in Rust: Choosing Your Guarantees](https://manishearth.github.io/blog/2015/05/27/wrapper-types-in-rust-choosing-your-guarantees/) - [Manish Goregaokar][]
* [Strategies for solving 'cannot move out of' borrowing errors in Rust](http://hermanradtke.com/2015/06/09/strategies-for-solving-cannot-move-out-of-borrowing-errors-in-rust.html) - [Herman J. Radtke III][]
* [Why Rust's ownership/borrowing is hard](http://softwaremaniacs.org/blog/2016/02/12/ownership-borrowing-hard/en/) - Ivan Sagalaev
* [& vs. ref in Rust patterns](http://xion.io/post/code/rust-patterns-ref.html) - Karol Kuczmarski
* [Interior mutability in Rust: what, why, how?](https://ricardomartins.cc/2016/06/08/interior-mutability) | [part 2](https://ricardomartins.cc/2016/06/25/interior-mutability-thread-safety) | [part 3](https://ricardomartins.cc/2016/07/11/interior-mutability-behind-the-curtain) - Ricardo Martins
* :star: [Rust Means Never Having to Close a Socket](http://blog.skylight.io/rust-means-never-having-to-close-a-socket/) - [Yehuda Katz][]
* [Understanding Lifetimes in Rust, part 1](https://mobiarch.wordpress.com/2015/06/29/understanding-lifetime-in-rust-part-i/) | [part 2](https://mobiarch.wordpress.com/2015/07/08/understanding-lifetime-in-rust-part-ii-3/) - Bibhas Bhattacharya
* [Some Notes on `Send` and `Sync`](https://huonw.github.io/blog/2015/02/some-notes-on-send-and-sync/) - [Huon Wilson][]
* [Sharing Coloring Books With Friends in Rust](http://jeenalee.com/2016/08/15/sharing-coloring-books-in-rust.html) - [Jeena Lee][]
* [Moving, Cloning, and Copying Coloring Books in Rust](http://jeenalee.com/2016/08/29/move-clone-copy.html) - [Jeena Lee][]
* [Ref patterns, destructuring, and invisible borrows](https://medium.com/@robertgrosse/ref-patterns-destructuring-and-invisible-borrows-2f8ae6902656) - Robert Grosse
* [Rust: A unique perspective](https://limpet.net/mbrubeck/2019/02/07/rust-a-unique-perspective.html) - Matt Brubeck
* [The Node Experiment - Exploring Async Basics with Rust](https://cfsamson.github.io/book-exploring-async-basics) - Carl Fredrik Samson
* [A closer look at Ownership in Rust](https://blog.thoughtram.io/ownership-in-rust/) - Pascal Precht
* [Understanding ownership in Rust](https://blog.logrocket.com/understanding-ownership-in-rust/) - Ukpai Ugochi

### Privacy

* :star: [Structure literals vs constructors in Rust](http://words.steveklabnik.com/structure-literals-vs-constructors-in-rust) - [Steve Klabnik][]

### Strings

* [String vs &str in Rust functions part 1](http://hermanradtke.com/2015/05/03/string-vs-str-in-rust-functions.html) | [part 2](http://hermanradtke.com/2015/05/06/creating-a-rust-function-that-accepts-string-or-str.html) | [part 3](http://hermanradtke.com/2015/05/29/creating-a-rust-function-that-returns-string-or-str.html) - [Herman J. Radtke III][]
* [From &str to Cow](http://blog.jwilm.io/from-str-to-cow/) - Joe Wilm
* [How do I convert a &str to a String in Rust?](https://blog.mgattozzi.dev/how-do-i-str-string) - [Michael Gattozzi][]
* [Rust: str vs String](http://www.ameyalokare.com/rust/2017/10/12/rust-str-vs-String.html) - Ameya Lokare
* [On dealing with owning and borrowing in public interfaces](https://phaazon.net/blog/on-owning-borrowing-pub-interface) - Dimitri Sabadie
* [Why Rust strings seem hard](https://www.brandons.me/blog/why-rust-strings-seem-hard) - Brandon Smith

### Syntax extensions

* :star: [Syntax extensions and regular expressions for Rust](http://blog.burntsushi.net/rust-regex-syntax-extensions/) - [Andrew Gallant][]

### Traits

* :star: [Abstraction without overhead: traits in Rust](http://blog.rust-lang.org/2015/05/11/traits.html) - [Aaron Turon][]
* [A series on trait objects part 1](https://huonw.github.io/blog/2015/01/peeking-inside-trait-objects) | [part 2](https://huonw.github.io/blog/2015/01/the-sized-trait) | [part 3](https://huonw.github.io/blog/2015/01/object-safety) | [part 4](https://huonw.github.io/blog/2015/05/where-self-meets-sized-revisiting-object-safety/) - [Huon Wilson][]
* [Rust traits for developer friendly libraries](https://benashford.github.io/blog/2015/05/24/rust-traits-for-developer-friendly-libraries/) - [Ben Ashford][]
* [Traits and trait objects](http://xania.org/201506/traits-and-trait-objects) - Matt Godbolt
* [Rust's Built-in Traits, the When, How & Why](https://llogiq.github.io/2015/07/30/traits.html) - [Llogiq][]
* [Where are you From::from](http://llogiq.github.io/2015/11/27/from-into.html) - [Llogiq][]
* [Gentle Intro to Type-level Recursion in Rust](https://beachape.com/blog/2017/03/12/gentle-intro-to-type-level-recursion-in-Rust-from-zero-to-frunk-hlist-sculpting/) - [Lloyd Chan][]
* [Traits and Trait Objects in Rust](https://joshleeb.com/posts/rust-traits-and-trait-objects/) - Josh Leeb-du Toit
* [A Quick Look at Trait Objects in Rust](https://tratt.net/laurie/blog/entries/a_quick_look_at_trait_objects_in_rust.html) - Laurence Tratt

### Unsafe

* [Unsafe Rust: An Intro and Open Questions](http://cglab.ca/~abeinges/blah/rust-unsafe-intro/) - [Alexis Beingessner][]
* [Memory Leaks are Memory Safe](https://huonw.github.io/blog/2016/04/memory-leaks-are-memory-safe/) - [Huon Wilson][]
* :star: [On Reference Counting and Leaks](http://smallcultfollowing.com/babysteps/blog/2015/04/29/on-reference-counting-and-leaks/) - [Niko Matsakis][]
* :star: [A Few More Remarks on Reference Counting and Leaks](http://smallcultfollowing.com/babysteps/blog/2015/04/30/a-few-more-remarks-on-reference-counting-and-leaks/) - [Niko Matsakis][]
* [Pre-pooping Your Pants With Rust](http://cglab.ca/~abeinges/blah/everyone-poops/) - [Alexis Beingessner][]
* :star: [Unsafe Abstractions](http://smallcultfollowing.com/babysteps/blog/2016/05/23/unsafe-abstractions/) - [Niko Matsakis][]
* :star: [The "Tootsie Pop" Model for Unsafe Code](http://smallcultfollowing.com/babysteps/blog/2016/05/27/the-tootsie-pop-model-for-unsafe-code/) - [Niko Matsakis][]

## Playground

* [Rust Playground](https://play.rust-lang.org)
* [alternative](http://play.integer32.com/)



## People

This is the official [Rust Team](http://www.rust-lang.org/team.html) and [Servo Team](https://github.com/orgs/servo/people)

Are you searching for a rustacean? [http://www.rustaceans.org/](http://www.rustaceans.org/)

Do you want to ask a question? [Users Forum](https://users.rust-lang.org/), [Stack Overflow](https://stackoverflow.com/questions/tagged/rust)

Do you want to meet them IRL? [Meetup groups](http://www.meetup.com/topics/rust/), [Community calendar](https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com), [Community talks list](https://github.com/rust-community/talks), [RustBridge](https://rustbridge.github.io/), [Time till Rust](https://timetill.rs/#/)

Go to rusty events? [The 2018 Rust Event Lineup](https://blog.rust-lang.org/2018/01/31/The-2018-Rust-Event-Lineup.html), [The 2019 Rust Event Lineup](https://blog.rust-lang.org/2019/05/20/The-2019-Rust-Event-Lineup.html)

Are you looking for a job? [RustJobs.rs](http://rustjobs.rs/)

Are you fast, friendly, and fearless? [Find something Rusty to work on!](https://www.rustaceans.org/findwork/starters)

Do you want to stay up to date? [The official blog](https://blog.rust-lang.org/), [This Week in Rust](https://this-week-in-rust.org/), [This Week in Rust Docs](http://guillaumegomez.github.io/this-week-in-rust-docs/), [The official reddit](https://www.reddit.com/r/rust/)

Do you want to find out why some historical decisions took place? [Chronicle.rs](https://github.com/mgattozzi/chronicle.rs)

### Fearless Rust Bloggers

A complete list could be found [here](https://users.rust-lang.org/t/fearless-rust-bloggers/16770)

* [Aaron Turon][] - [blog](http://aturon.github.io/)
* [Andrew Gallant][] - [blog](http://blog.burntsushi.net/)
* [Andrew Hobden][] - [blog](https://hoverbear.org/tags/#rust)
* [Brian Anderson][] - [blog](https://brson.github.io/blog/index.html)
* [Christoph Burgdorf][] - [blog](https://cburgdorf.wordpress.com/)
* [Chris Morgan][] - [blog](https://chrismorgan.info/blog/tags/rust/)
* [Felix S Klock II][] - [blog](http://blog.pnkfx.org/)
* [Huon Wilson][] - [blog](https://huonw.github.io/blog/)
* [Jonathan Turner][] - [blog](http://jntrnr.github.io)
* [Llogiq][] - [blog](http://llogiq.github.io/)
* [Manish Goregaokar][] - [blog](https://manishearth.github.io/)
* [Nick Cameron][] - [blog](http://featherweightmusings.blogspot.fr/)
* [Niko Matsakis][] - [blog](http://smallcultfollowing.com/babysteps/)
* [Patrick Walton][] - [blog](https://pcwalton.github.io/)
* [Yehuda Katz][] - [blog](http://yehudakatz.com/)
* [Steve Klabnik][] - [blog](http://words.steveklabnik.com/)

Don't forget [Ferris](http://www.rustacean.net/) the unofficial mascot.

## Tutorials & Workshop Materials

These are slides and materials from brick-and-mortar workshops about Rust.
While they're unlikely to help a student learning independently, they may be
of interest if you're running a workshop on Rust.

* Workshop [slides and exercises](http://www.rust-tutorials.com/RustConf17/) from RustConf 2017.
* Niko Matsakis's [rust tutorializer](https://github.com/nikomatsakis/rust-tutorializer) framework
* Niko Matsakis's [ownership, borrowing, traits, structs, and threading tutorials](https://github.com/nikomatsakis/rust-tutorials-keynote), keynote files
* Niko Matsakis's [concurrency tutorial](https://github.com/nikomatsakis/concurrency-tutorial) from December 2015
* Niko Matsakis's [Mozlando Tutorial](http://smallcultfollowing.com/20151209/) includes slides and play.rust-lang.org demos
* Jim Blandy's [exercises](https://github.com/jimblandy/exercises)
* Dan Callahan's [Python Rust FFI](https://github.com/callahad/python-rust-ffi) examples
* Nick Cameron's [oopsla slides and exercises](http://ncameron.org/oopsla15.html)
* Florian Gilcher's [mailbox tutorial](https://github.com/skade/mailbox) takes Hello World to a whole new concurrent and networked level
* Carol Nichols' [Intro to Rust](https://github.com/carols10cents/intro-to-rust) that presents the guessing game and ownership in a similar manner as the book
* Jonathan Pallant's [Rust on the Raspberry Pi tutorial (using a Sense HAT)](https://github.com/thejpster/pi-workshop-rs)

A few universities have had classes about Rust. Here are links to their public resources.

* University of Pennsylvania [CIS 198: Rust Programming](https://www.cis.upenn.edu/~cis198/), Fall 2019, Rust 1.37.0. Slides linked from Schedule page. [Github](https://github.com/upenn-cis198)

<!-- Rustaceans -->
[Aaron Turon]: https://github.com/aturon
[Alex Crichton]: https://github.com/alexcrichton
[Alexis Beingessner]: https://github.com/Gankro
[Andrew Gallant]: https://github.com/BurntSushi
[Andrew Hobden]: https://github.com/Hoverbear
[Ben Ashford]: https://github.com/benashford
[Brian Anderson]: https://github.com/brson
[Carl Lerche]: https://github.com/carllerche
[Carol Nichols]: https://github.com/carols10cents
[Chris Krycho]: https://github.com/chriskrycho
[Chris Morgan]: https://github.com/chris-morgan
[Christoph Burgdorf]: https://github.com/cburgdorf
[Daniel Keep]: https://github.com/DanielKeep
[Dan Callahan]: https://github.com/callahad
[Eduard Burtescu]: https://github.com/eddyb
[Felix S Klock II]: https://github.com/pnkfelix
[Gulshan Singh]: https://github.com/gsingh93
[Herman J. Radtke III]: https://github.com/hjr3
[Jakub Bukaj]: https://github.com/jakub-
[Jeena Lee]: https://github.com/jeenalee
[Jeremiah Peschka]: https://github.com/peschkaj
[Jim Blandy]: https://github.com/jimblandy
[Jorge Aparicio]: https://github.com/japaric
[Josh Matthews]: https://github.com/jdm
[Jonathan Turner]: https://github.com/jonathandturner
[Llogiq]: https://github.com/llogiq
[Luca Palmieri]: https://github.com/LukeMathWalker
[Luqman Aden]: https://github.com/luqmana
[Lloyd Chan]: https://github.com/lloydmeta
[Huon Wilson]: https://github.com/huonw
[Manish Goregaokar]: https://github.com/Manishearth
[Michael Gattozzi]: https://github.com/mgattozzi
[Nick Cameron]: https://github.com/nrc
[Niko Matsakis]: https://github.com/nikomatsakis
[Pascal Hertleif]: https://github.com/killercup
[Patrick Walton]: https://github.com/pcwalton
[Seo Sanghyeon]: https://github.com/sanxiyn
[Simon Sapin]: https://github.com/SimonSapin
[Steve Donovan]: https://github.com/stevedonovan
[Steve Klabnik]: https://github.com/steveklabnik
[Steven Fackler]: https://github.com/sfackler
[Tetsuharu OHZEKI]: https://github.com/saneyuki
[Tim McNamara]: https://github.com/timClicks
[Yehuda Katz]: https://github.com/wycats
[Dumindu Madunuwan]: https://github.com/dumindu

## Similar projects

* [Curated Resources to Learn Rust](https://hackr.io/tutorials/learn-rust) - Hackr.io
* [Rust Anthology Master List](https://github.com/brson/rust-anthology/blob/master/master-list.md) - [Brian Anderson][]
* [Read Rust](https://readrust.net/)

<details>
  <summary>RUST BOOK LIST (Click to expand)</summary>


Rust Books
====
* [Books](#books)
 * [Starter Books](#starter-books)
 * [Advanced Books](#advanced-books)
* [Resources](#resources)

**Books**
====

**Starter Books**
----

### [The Rust Programming Language](https://doc.rust-lang.org/book/) *Free*

Welcome! This book will teach you about the Rust programming language. Rust is a systems programming language focused on three goals: safety, speed, and concurrency. It maintains these goals without having a garbage collector, making it a useful language for several use cases other languages aren’t good at: embedding in other languages, programs with specific space and time requirements, and writing low-level code, like device drivers and operating systems. It improves on current languages targeting this space by having several compile-time safety checks that produce no runtime overhead while eliminating all data races. Rust also aims to achieve ‘zero-cost abstractions’ even though some of these abstractions feel like those of a high-level language. Even then, Rust still allows precise control like a low-level language would.

### [Welcome to Rust-101](https://www.ralfj.de/projects/rust-101/main.html) *Free*

This is Rust-101, a small tutorial for the Rust language. It is intended to be an interactive, hands-on course: I believe the only way to really learn a language is to write code in it, so you should be coding during the course.
If you have any questions that are not answered here, check out the "Additional Resources" below. In particular, the IRC channel is filled with awesome people willing to help you! I spent lots of time there ;-)
I will assume some familiarity with programming, and hence not explain the basic concepts common to most languages. Instead, I will focus on what makes Rust special.

### [Rust by Example](https://doc.rust-lang.org/rust-by-example/) *Free*

Rust by Example (RBE) is a collection of runnable examples that illustrate various Rust concepts and standard libraries. To get even more out of these examples, don't forget to [install Rust locally](http://www.rust-lang.org/install.html) and check out the [official docs](http://doc.rust-lang.org/std/). Additionally for the curious, you can also [check out the source code for this site](https://github.com/rust-lang/rust-by-example).

### [Easy Rust](https://dhghomon.github.io/easy_rust/) *Free*

Rust is a new language that already has good textbooks. But sometimes its textbooks are difficult because they are for native English speakers. Many companies and people now learn Rust, and they could learn faster with a book that has easy English. This textbook is for these companies and people to learn Rust with simple English.

### [Why Rust?](http://www.oreilly.com/programming/free/why-rust.csp)

<img src="http://covers.oreillystatic.com/images/0636920040446/cat.gif" width="120px"/>

While systems programming languages have greatly evolved since the introduction of C more than 40 years ago, our capacity for dumb mistakes with enormous consequences has remained unchanged, with vivid examples regularly in the news. This O'Reilly report examines Rust, a new systems programming language that combines safety and security with performance on a par with C and C++.

### [Learning Rust](https://www.amazon.com/Learning-Rust-comprehensive-writing-applications/dp/1785884301)

<img src="https://images-na.ssl-images-amazon.com/images/I/41RBJ0J9WOL._SX258_BO1,204,203,200_.jpg" width="120px"/>

Rust is a highly concurrent and high-performance language that focuses on safety and speed, memory management, and writing clean code. It also guarantees thread safety, and it aims to improve the performance of existing applications. It has been backed by Mozilla to solve the critical problem of concurrency.

### [Beginning Rust - From Novice to Professional](https://www.apress.com/us/book/9781484234679) 

<img src="https://media.springernature.com/full/springer-static/cover-hires/book/978-1-4842-3468-6" width="120px"/>

Learn to program with Rust in an easy, step-by-step manner on Unix, Linux shell, macOS and the Windows command line.  As you read this book, you’ll build on the knowledge you gained in previous chapters and see what Rust has to offer.  

Beginning Rust starts with the basics of Rust, including how to name objects, control execution flow, and handle primitive types. You’ll see how to do arithmetic, allocate memory, use iterators, and handle input/output. Once you have mastered these core skills, you’ll work on handling errors and using the object-oriented features of Rust to build robust Rust applications in no time.

Only basic knowledge of programming is required, preferably in C or C++. To understand this book, it's enough to know what integers and floating-point numbers are, and to distinguish identifiers from string literals.

### [Rust Cookbook](https://www.amazon.com/Rust-Cookbook-Understand-management-concurrency/dp/178588025X) 

<img src="https://images-na.ssl-images-amazon.com/images/I/516rEveOb2L._SX258_BO1,204,203,200_.jpg" width="120px"/>

This book will help you understand the core concepts of the Rust language, enabling you to develop efficient and high-performance applications by incorporating features such as zero-cost abstraction and better memory management. Delve into advanced-level concepts such as error handling, macros, crates, and parallelism in Rust. Toward the end of the book, learn how to create HTTP servers and web services, building a strong foundational knowledge in server-side programming and enabling to deliver solutions to build high-performance and safer production-level web applications and services using Rust.

### [Rust Standard Library Cookbook](https://www.amazon.com/Rust-Standard-Library-Cookbook-leverage/dp/1788623924)

<img src="https://images-na.ssl-images-amazon.com/images/I/51mi9EEU6pL.jpg" width="120px"/>

Mozilla’s Rust is gaining much attention with amazing features and a powerful library. This book will take you through varied recipes to teach you how to leverage the Standard library to implement efficient solutions.

The book begins with a brief look at the basic modules of the Standard library and collections. From here, the recipes will cover packages that support file/directory handling and interaction through parsing. You will learn about packages related to advanced data structures, error handling, and networking. You will also learn to work with futures and experimental nightly features. The book also covers the most relevant external crates in Rust.

### [Network Programming with Rust](https://www.oreilly.com/library/view/network-programming-with/9781788624893/)

<img src="https://www.safaribooksonline.com/library/cover/9781788624893/360h/" width="120px">

Rust is low-level enough to provide fine-grained control over memory while providing safety through compile-time validation. This makes it uniquely suitable for writing low-level networking applications.

This book is divided into three main parts that will take you on an exciting journey of building a fully functional web server. The book starts with a solid introduction to Rust and essential networking concepts. This will lay a foundation for, and set the tone of, the entire book. In the second part, we will take an in-depth look at using Rust for networking software. From client-server networking using sockets to IPv4/v6, DNS, TCP, UDP, you will also learn about serializing and deserializing data using serde. The book shows how to communicate with REST servers over HTTP. The final part of the book discusses asynchronous network programming using the Tokio stack. Given the importance of security for modern systems, you will see how Rust supports common primitives such as TLS and public-key cryptography.

### [Rust Programming by Example](https://www.amazon.com/Rust-Programming-Example-concurrent-applications/dp/1788390636)

<img src="https://images-na.ssl-images-amazon.com/images/I/416Cm3m8EmL._SX404_BO1,204,203,200_.jpg" width="120px"/>

Beginning with an introduction to Rust, you’ll learn the basic aspects such as its syntax, data types, functions, generics, control flows, and more. After this, you’ll jump straight into building your first project, a Tetris game. Next, you’ll build a graphical music player and work with fast, reliable networking software using Tokio, the scalable and productive asynchronous IO Rust library.

Throughout this book, you’ll explore various features of Rust Programming including its SDL features, event loop, File I/O, and the famous GTK+ widget toolkit. Through these projects, you’ll see how well Rust performs in terms of concurrency—including parallelism, reliability, improved performance, generics, macros, and thread-safety. We’ll also cover some asynchronous and reactive programming aspects of Rust.

### [Rust Quick Start Guide](https://www.amazon.com/Rust-Quick-Start-Guide-programming/dp/1789616700)

<img src="https://images-na.ssl-images-amazon.com/images/I/41MPpgq643L._SX404_BO1,204,203,200_.jpg" width="120px"/>

Get familiar with writing programs in the trending new systems programming language that brings together the powerful performance of low-level languages with advanced features like thread-safety in multi-threaded code.

### [Rust in Action](https://www.manning.com/books/rust-in-action)

<img src="https://images.manning.com/360/480/resize/book/b/5b94de7-93ef-4650-bc58-5485bfc1e82c/McNamara-Rust-HI.png" width="120px"/>

Rust in Action is a book for intermediate programmers who want to explore the world of the Rust programming language. It's intended for people who may have exhausted the free material on the web, but who still want to learn more. It's is different from other material on Rust programming because it also teaches you about systems programming along the way. You'll be able to learn more about how a CPU works, how computers keep time, what pointers are and how your network card and keyboard tell the CPU that they have input ready to read.

It’s unique from the point of view of systems programming books too - as almost every example works on Windows! If you are the kind of learner who enjoys worked examples, you'll enjoy reading this book.

### [A Gentle Introduction to Rust](https://stevedonovan.github.io/rust-gentle-intro/) *Free*

<img src="https://stevedonovan.github.io/rust-gentle-intro/PPrustS.png" width="120px"/>

Rust is a statically and strongly typed systems programming language. statically means that all types are known at compile-time, strongly means that these types are designed to make it harder to write incorrect programs. A successful compilation means you have a much better guarantee of correctness than with a cowboy language like C. systems means generating the best possible machine code with full control of memory use. So the uses are pretty hardcore: operating systems, device drivers and embedded systems that might not even have an operating system. However, it's a very pleasant language to write normal application code in as well.

The big difference from C and C++ is that Rust is safe by default; all memory accesses are checked. It is not possible to corrupt memory by accident.

### [Practical Machine Learning with Rust: Creating Intelligent Applications in Rust](https://www.amazon.com/Practical-Machine-Learning-Rust-Applications/dp/1484251202)

<img src="https://github.com/Apress/practical-machine-learning-w-rust/blob/master/9781484251201.jpg" width="120px"/>

Machine Learning in Rust has been neglected for quite some time by the community. With many disparate crates scattered through the cosmos, this book is an attempt at unifying all the information and usages that are out there and kind of shake the community into action. Data is the new frontier and Rust has to be a part of that.

After reading Practical Machine Learning with Rust, you will have a solid understanding of creating high computation libraries using Rust. Armed with the knowledge of this amazing language, you will be able to create applications that are more performant, memory safe, and less resource-heavy.

### [Rust Web Development](https://www.manning.com/books/rust-web-development)

<img src="https://images.manning.com/360/480/resize/book/b/74ea4b7-da90-40ab-a2e8-52a72daecdb4/Gruber-MEAP-HI.png" width="120px" />

Rust Web Development is a hands-on guide to building server-based web applications with Rust. If you’ve built web servers using Java, C#, or PHP, you’ll instantly fall in love with the performance and development experience Rust delivers. This book shows you how to work efficiently using pure Rust, along with important Rust libraries such as tokio for async runtimes, warp for web servers and APIs, and reqwest to run external HTTP requests.

You can hand this book over to your newly hired developer and onboard them with this book. It contains very practical examples and patterns, and serves as a solid foundation for future exploration into the topic.

### [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust)

<img src="https://images.manning.com/192/256/resize/book/f/6b2c7cf-d21a-4c6f-b243-8cc9b635a6c6/Mara-RR-MEAP-HI.png" width="120px" />

Refactoring to Rust teaches you to combine your favorite programming language with high-performance Rust code. Author Lily Mara introduces Rust in her easy-to-read style, clearly explaining the language's unique syntax and concepts. You’ll augment programs with Rust hands-on with approachable examples like solving FizzBuzz with Rust’s pattern matching and gaining enormous runtime speedups to Python code. When you’re done, you’ll have mastered techniques for building Rust plugins you can apply to all kinds of existing software, from games to data tools.


**Advanced Books**
---

### [The Rustonomicon](https://doc.rust-lang.org/nightly/nomicon/) *Free*

This book digs into all the awful details that are necessary to understand to write correct Unsafe Rust programs. Due to the nature of this problem, it may lead to unleashing untold horrors that shatter your psyche into a billion infinitesimal fragments of despair.

Should you wish a long and happy career of writing Rust programs, you should turn back now and forget you ever saw this book. It is not necessary. However, if you intend to write unsafe code -- or just want to dig into the guts of the language -- this book contains invaluable information.

### [Rust Patterns](https://rust-unofficial.github.io/patterns/) *Free*

There are many problems that share the same form. Due to the fact that Rust is not object-oriented, design patterns vary with respect to other object-oriented programming languages. While the details are different, since they have the same form they can be solved using the same fundamental methods.

This book collects social norms of the community and demonstrates methods to solve common problems and reveals common pitfalls you will stuble upon when writing software in Rust.

### [Programming Rust 2nd Edition](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/)

<img src="https://learning.oreilly.com/library/cover/9781492052586/250w/" width="120px"/>

This practical book introduces systems programmers to Rust, the new and cutting-edge language. You’ll learn how Rust offers the rare and valuable combination of statically verified memory safety and low-level control—imagine C++, but without dangling pointers, null pointer dereferences, leaks, or buffer overruns.

### [Mastering Rust 2nd Edition](https://www.amazon.com/Mastering-Rust-memory-concurrency-features/dp/1789346576)

<img src="https://images-na.ssl-images-amazon.com/images/I/51sYHUXdKyL._SX404_BO1,204,203,200_.jpg" width="120px"/>

Rust is an empowering language that provides a rare combination of safety, speed, and zero-cost abstractions. Mastering Rust – Second Edition is filled with clear and simple explanations of the language features along with real-world examples, showing you how you can build robust, scalable, and reliable programs.

This second edition of the book improves upon the previous one and touches on all aspects that make Rust a great language. We have included the features from the latest Rust 2018 edition such as the new module system, the smarter compiler, helpful error messages, and the stable procedural macros. You’ll learn how Rust can be used for systems programming, network programming, and even on the web. You’ll also learn techniques such as writing memory-safe code, building idiomatic Rust libraries, writing efficient asynchronous networking code, and advanced macros. The book contains a mix of theory and hands-on tasks so you acquire the skills as well as the knowledge, and it also provides exercises to hammer the concepts in.

After reading this book, you will be able to implement Rust for your enterprise projects, write better tests and documentation, design for performance, and write idiomatic Rust code.

### [Rust Essentials - Second Edition](https://www.amazon.com/Rust-Essentials-Ivo-Balbaert/dp/1785285769) 

<img src="https://images-na.ssl-images-amazon.com/images/I/514o8ZgJouL._SX403_BO1,204,203,200_.jpg" width="120px"/>

This book starts off with the argumentation of Rust's unique place in today's landscape of programming languages. Install Rust and learn how to work with its package manager Cargo. The various concepts are introduced step by step: variables, types, functions, and control structures to lay the groundwork. Then explore more structured data such as strings, arrays, and enums, and see how pattern matching works.

Throughout all this, this book emphasizes the unique ways of reasoning that the Rust compiler uses to produce safe code. Next look at Rust's specific way of error handling, and the overall importance of traits in Rust code. The pillar of memory safety is treated in depth as we explore the various pointer kinds. Next, see how macros can simplify code generation, and how to compose bigger projects with modules and crates. Finally, discover how we can write safe concurrent code in Rust and interface with C programs, get a view of the Rust ecosystem, and explore the use of the standard library.

### [Hands-On Concurrency with Rust](https://www.amazon.com/Hands-Concurrency-Rust-Confidently-memory-safe/dp/1788399978)

<img src="https://images-na.ssl-images-amazon.com/images/I/51L1ttVxCbL._SX404_BO1,204,203,200_.jpg" width="120px"/>

This book will teach you how to manage program performance on modern machines and build fast, memory-safe, and concurrent software in Rust. It starts with the fundamentals of Rust and discusses machine architecture concepts. You will be taken through ways to measure and improve the performance of Rust code systematically and how to write collections with confidence. You will learn about the Sync and Send traits applied to threads, and coordinate thread execution with locks, atomic primitives, data-parallelism, and more.

The book will show you how to efficiently embed Rust in C++ code and explore the functionalities of various crates for multithreaded applications. It explores implementations in depth. You will know how a mutex works and build several yourself. You will master radically different approaches that exist in the ecosystem for structuring and managing high-scale systems.

### [Hands-On Functional Programming in Rust](https://www.amazon.com/Hands-Functional-Programming-Rust-applications-ebook/dp/B07C5S4729)

<img src="https://images-na.ssl-images-amazon.com/images/I/51UMHEimRVL.jpg" width="120px"/>

Functional Programming allows developers to divide programs into smaller, reusable components that ease the creation, testing, and maintenance of software as a whole. Combined with the power of Rust, you can develop robust and scalable applications that fulfill modern day software requirements. This book will help you discover all the Rust features that can be used to build software in a functional way.

We begin with a brief comparison of the functional and object-oriented paradigms to different problems and patterns. We then quickly look at the patterns of control flow, data the abstractions of these unique to Functional Programming. The next part covers how to create functional apps in Rust; mutability and ownership, which are exclusive to Rust, are also discussed. Pure functions are examined next and you'll master closures, their various types, and currying. We also look at implementing concurrency through functional design principles and metaprogramming using macros. Finally, we look at best practices for debugging and optimization.

By the end of the book, you will be familiar with the functional approach of programming and will be able to use these techniques daily.

### [Rust High Performance](https://www.amazon.com/Rust-High-Performance-performance-applications/dp/178839948X)

<img src="https://images-na.ssl-images-amazon.com/images/I/51gtUcYaPrL._SX404_BO1,204,203,200_.jpg" width="120px"/>

At times, it is difficult to get the best performance out of Rust. This book teaches you to optimize the speed of your Rust code to the level of languages such as C/C++. You'll understand and fix common pitfalls, learn how to improve your productivity by using metaprogramming, and speed up your code by concurrently executing parts of it safely and easily. You will master the features of the language which will make you stand out and use them to improve the efficiency of your algorithms

The book begins with a gentle introduction to help you identify bottlenecks when programming in Rust. We highlight common performance pitfalls, along with strategies to detect and resolve these issues early. We move on to mastering Rust's type system, which will enable us to create impressive optimizations in both performance and safety at compile time. You will then learn how to effectively manage memory in Rust, mastering the borrow checker. We move on to measuring performance and you will see how this affects the way you write code. Moving ahead, you will perform metaprogramming in Rust to boost the performance of your code and your productivity. You will finally learn parallel programming in Rust, which enables efficient and faster execution by using multithreading and asynchronous programming.

### [Zero To Production In Rust](https://zero2prod.com)

<img src="https://www.zero2prod.com/assets/img/book2.png" width="120px"/>

If you want to learn how to use Rust for backend development, this is the place.

Rust's adoption is at an all-time high: more and more companies are trying it out and hiring for it.  
If you are interested in building APIs with Rust, **Zero To Production** is the ideal starting point for your Rust journey.  
You will learn by doing: we will start from scratch and build together, step by step, a fully functional email newsletter backend API.  

You'll learn how to:

  * Navigate and leverage Rust's crates ecosystem
  * Structure your application to make it modular and extensible
  * Write tests, from single units to full-blown integration tests
  * Model your domain using the type system to enforce invariants
  * Collect logs, traces and metrics to observe the state of your application
  * Set up a robust continuous integration and continuous deployment pipeline for your Rust projects

### [Programming WebAssembly with Rust](https://pragprog.com/book/khrust/programming-webassembly-with-rust)

<img src="https://i.ibb.co/ccL8zzC/khrust.jpg" width="120px"/>

WebAssembly is more than just a revolutionary new technology. It’s reshaping how we build applications for the web and beyond. Where technologies like ActiveX and Flash have failed, you can now write code in whatever language you prefer and compile to WebAssembly for fast, type-safe code that runs in the browser, on mobile devices, embedded devices, and more. Combining WebAssembly’s portable, high-performance modules with Rust’s safety and power is a perfect development combination.

Learn how WebAssembly’s stack machine architecture works, install low-level wasm tools and discover the dark art of writing raw wast code. Build on that foundation and learn how to compile WebAssembly modules from Rust by implementing the logic for a checkers game. Create wasm modules in Rust to interoperate with JavaScript in many compelling ways. Apply your new skills to the world of non-web hosts, and create everything from an app running on a Raspberry Pi that controls a lighting system, to a fully-functioning online multiplayer game engine where developers upload their own arena-bound WebAssembly combat modules.

Get started with WebAssembly today, and change the way you think about the web.

### [Step Ahead with Rust: Systems Programming in Rust](https://www.armstrong-publications.com/product/step-ahead-with-rust-super-combo/)

<img src="https://images-na.ssl-images-amazon.com/images/I/41ztdWA7yCL.jpg" width="120px"/>

From basic programming patterns to a peek under the hood of the language, Step Ahead with Rust aims to help you move from writing programs to building software in Rust. This book will show you the most important features of the Rust language, including cargo, type system, iterators and more. By the end of this book, you should be familiar with far more of them, and ready to tackle the rest of the advanced topics. 

As you progress through the book, we recommend taking the time to experiment with what is presented in its pages. This book is all about the practical application of Rust, so applying it in practice is expected. The book covers: Cargo, Rust Type System, Iterators, Macros, Ownership, Borrowing and Lifetimes, Unsafe Patterns, Concurrency. A Step Ahead with Rust reader is expected to be a moderately experienced developer looking to improve their Rust development skills.

### [Hands-On Microservices with Rust 2018: How To Build Scalable and Reliable RESTful Microservices](https://www.amazon.co.uk/Hands-Microservices-Rust-2018-Scalable/dp/1789342759/ref=sr_1_6?s=books&ie=UTF8&qid=1545340800&sr=1-6&keywords=rust) *will be published in April 2019*

<img src="https://images-na.ssl-images-amazon.com/images/I/518eneKG4ML._SX260_.jpg" width="120px"/>

Microservice architecture is sweeping the world as the de facto pattern to build web-based applications. Rust is a language particularly well suited to building microservices. It is a new system programming language that offers a practical and safe alternative to C.

This book describes web development using the Rust programming language and will get you up and running with modern web frameworks and crates with examples of RESTful microservices creation. You will deep dive into Reactive programming, asynchronous programming and split our web application into a set of concurrent actors. The book provides several highly accurate HTTP-handling examples with manageable memory allocations. You will be walked through stateless high-performance microservices which are ideally suitable for computation or caching tasks and get to stateful microservices which are filled with persistent data and database interactions. As we move along, you will learn to use Rust macros to describe business or protocol entities of our application and compile them into native structs which will be performed at full speed with the help of the server's CPU.

Finally, you will be taken through examples of how to test and debug microservices and pack them to a tiny monolithic binary or put it into a container and deploy it to modern cloud platforms such as AWS.

### [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/book/index.html) *Free* (this is a work in progress)

This book is an attempt to distil the Rust community's collective knowledge of Rust macros. The book will introduce Rust's Macro-By-Example system: *macro_rules!*. Rather than trying to cover it based on practical examples, it will instead attempt to give you a complete and thorough explanation of how the system works. As such, this is intended for people who just want the system as a whole explained, rather than be guided through it.

### [Hands-On Data Structures and Algorithms with Rust](https://www.packtpub.com/application-development/hands-data-structures-and-algorithms-rust)

<img src="https://images-na.ssl-images-amazon.com/images/I/51Fh6vCPQlL._SX258_BO1,204,203,200_.jpg" width="120px"/>

The book begins with an introduction to Rust data structures and algorithms, while also covering essential language constructs. You will learn how to store data using linked lists, arrays, stacks, and queues. You will also learn how to implement sorting and searching algorithms. You will learn how to attain high performance by implementing algorithms to string data types and implement hash structures in algorithm design. The book will examine algorithm analysis, including Brute Force algorithms, Greedy algorithms, Divide and Conquer algorithms, Dynamic Programming, and Backtracking.

By the end of the book, you will have learned how to build components that are easy to understand, debug, and use in different applications.

### [The Complete Rust Programming Reference Guide: Design, develop, and deploy effective software systems using the advanced constructs of Rust](https://www.amazon.com/Complete-Rust-Programming-Reference-Guide/dp/1838828109)

<img src="https://images-na.ssl-images-amazon.com/images/I/51kBrALkNpL._SX404_BO1,204,203,200_.jpg" width="120px"/>

Rust is a powerful language with a rare combination of safety, speed, and zero-cost abstractions. This Learning Path is filled with clear and simple explanations of its features along with real-world examples, demonstrating how you can build robust, scalable, and reliable programs.
You'll get started with an introduction to Rust data structures, algorithms, and essential language constructs. Next, you will understand how to store data using linked lists, arrays, stacks, and queues. You'll also learn to implement sorting and searching algorithms, such as Brute Force algorithms, Greedy algorithms, Dynamic Programming, and Backtracking. As you progress, you'll pick up on using Rust for systems programming, network programming, and the web. You'll then move on to discover a variety of techniques, right from writing memory-safe code, to building idiomatic Rust libraries, and even advanced macros.
By the end of this Learning Path, you'll be able to implement Rust for enterprise projects, writing better tests and documentation, designing for performance, and creating idiomatic Rust code.

This Learning Path includes content from the following Packt products:
* Mastering Rust - Second Edition by Rahul Sharma and Vesa Kaihlavirta
* Hands-On Data Structures and Algorithms with Rust by Claus Matzinger

### [Creative Projects for Rust Programmers](https://www.packtpub.com/programming/creative-projects-for-rust-programmers)

<img src="https://www.packtpub.com/media/catalog/product/cache/bf3310292d6e1b4ca15aeea773aca35e/9/7/9781789346220-original_125.png" width="120px"/>

A practical guide to understanding the latest features of the Rust programming language, useful libraries, and frameworks that will help you design and develop interesting projects

Learn:

* Access TOML, JSON, and XML files and SQLite, PostgreSQL, and Redis databases
* Develop a RESTful web service using JSON payloads
* Create a web application using HTML templates and JavaScript and a frontend web application or web game using WebAssembly
* Build desktop 2D games
* Develop an interpreter and a compiler for a programming language
* Create a machine language emulator
* Extend the Linux Kernel with loadable modules

### [Black Hat Rust](https://kerkour.com/black-hat-rust/)

<img src="https://kerkour.com/imgs/black_hat_rust_cover.png" width="120px"/>

Applied offensive security with the Rust programming language, While the Rust Book does an excellent job teaching What is Rust, a book about Why and How to Rust was missing.  

What are the motivations of the attackers? How can they break seemingly so easily into any network? What do they do to their victims? We will put on our black hat and explore the world of offensive security, whether it be cyber attacks, cybercrimes, or cyberwar. Scanners, exploits, phishing toolkit, implants… From theory to practice, we will explore the arcane of offensive security and build our own offensive tools with the Rust programming language, Stack Overflow’s most loved language for five years in a row.  

Which programming language allows to craft shellcodes, build servers, create phishing pages? Before Rust, none! Rust is the long-awaited one-size-fits-all programming language meeting all those requirements thanks to its unparalleled guarantees and feature set.

### [Rust for Rustaceans](https://nostarch.com/rust-rustaceans)

<img src="https://nostarch.com/sites/default/files/styles/uc_product/public/RustforRustaceans_cover.png" width="120px"/>

For developers who’ve mastered the basics, this book is the next step on your way to professional-level programming in Rust. It covers everything you need to build and maintain larger codebases, write powerful and flexible applications and libraries, and confidently expand the scope and complexity of your projects.

Author Jon Gjengset takes you deep into the Rust programming language, dissecting core topics like ownership, traits, concurrency, and unsafe code. You’ll explore key concepts like type layout and trait coherence, delve into the inner workings of concurrent programming and asynchrony with async/await, and take a tour of the world of no_std programming. Gjengset also provides expert guidance on API design, testing strategies, and error handling, and will help develop your understanding of foreign function interfaces, object safety, procedural macros, and much more.

You'll Learn:

    1)How to design reliable, idiomatic, and ergonomic Rust programs based on best principles
    2)Effective use of declarative and procedural macros, and the difference between them
    3)How asynchrony works in Rust
    4)What it means for code to be unsafe, and best practices for writing and interacting with unsafe functions and traits
    5)How to organize and configure more complex Rust projects so that they integrate nicely with the rest of the ecosystem
    6)How to write Rust code that can interoperate with non-Rust libraries and systems, or run in constrained and embedded environments 

Brimming with practical, pragmatic insights that you can immediately apply, Rust for Rustaceans helps you do more with Rust, while also teaching you its underlying mechanisms.

### [Rust Crash Course](https://amzn.to/3P8Gxuz)

<img src="https://cdn.shopify.com/s/files/1/0514/0014/7144/products/576_front_775x975.jpg" width="120px"/>

Rust is a sophisticated systems programming language for speed, memory safety, and parallelism. This book gives you a fast introduction to Rust so that you may get started with low-level system programming and developing web applications, network services, and embedded programmes.

The book begins with instructions on setting up the Rust environment, developing a "hello world" programme, and getting started with cargo, the Rust package manager and the build tool. The book is a crash course, although it covers fundamental programming principles like variables and mutability, data types, comments, and control flow. Very precisely, topics such as ownership, borrowing, structs, enums, and other collections are covered. Error handling, memory management, and concurrency are well-demonstrated using practical projects. The book explains how to construct automated tests, write multithreaded applications, and utilise common data structures without difficulty. The book concludes with several hands-on projects, including creating a CLI application, a web app, a binary image classifier, and an embedded programme.

You'll learn:

1) Learn Rust's Cargo, fundamental concepts, collections, generic data types, iterators, and closures.
2) Learn to write and experience the working of memory-safe programs.
3) Implement and practice various data structures and algorithms.

This book is intended for software developers and system programmers interested in Rust as a C/C++ alternative. This book is also available to students interested in learning systems programming using Rust. The book assumes you have prior knowledge of basic programming concepts or any other programming language.

**Resources**
====

### [Learn Rust with examples](https://github.com/rust-lang/rust-by-example)

### [The Rust Programming Language](https://www.youtube.com/watch?v=d1uraoHM8Gg)

### [Are We Learning Yet?](http://www.arewelearningyet.com/): List of resources for machine learning in Rust

### [Are We Web Yet?](http://www.arewewebyet.org/): List of resources for web development in Rust

Contributing
====
Your contributions are always welcome, just follow [the rules](https://github.com/sger/RustBooks/blob/master/CONTRIBUTING.md)!

License
====
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
</details>