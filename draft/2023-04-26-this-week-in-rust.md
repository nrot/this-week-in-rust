Title: This Week in Rust 492
Number: 492
Date: 2023-04-26
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](https://www.rust-lang.org/) is a programming language empowering everyone to build reliable and efficient software.
This is a weekly summary of its progress and community.
Want something mentioned? Tag us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) on Twitter or [@ThisWeekinRust](https://mastodon.social/@thisweekinrust) on mastodon.social, or [send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

## Updates from Rust Community

<!--

Dear community contributors:
Please read README.md for guidance on submissions.
Each submitted link should be of the form:

* [Title of the Linked Page](https://example.com/my_article)

If you don't know which category to use, feel free to submit a PR anyway
and just ask the editors to select the category.

-->

### Official

* [Announcing Rust 1.69.0 | Rust Blog](https://blog.rust-lang.org/2023/04/20/Rust-1.69.0.html)

### Foundation

### Newsletters

### Project/Tooling Updates

* [Changelog #178](https://rust-analyzer.github.io/thisweek/2023/04/24/changelog-178.html)
* [`regex` 1.8.0 release notes](https://github.com/rust-lang/regex/blob/master/CHANGELOG.md#180-2023-04-20)

### Observations/Thoughts

* [Is Rust a worthy contender for web development?](https://joshmo.hashnode.dev/can-rust-beat-javascript-in-2023)
* [Bringing runtime checks to compile time in Rust](https://ktkaufman03.github.io/blog/2023/04/20/rust-compile-time-checks/)
* [video] [Embeddable Rust](https://www.electronicdesign.com/technologies/embedded/software/video/21263235/electronic-design-embeddable-rust)

### Rust Walkthroughs

* [Foresterre's place | Using the todo! macro to prototype your API in Rust](https://foresterre.github.io/posts/todo-macro-rust/)
* [Generics and Const Generics in Rust](https://sanjuvi.github.io/Blog/posts/Rust%20Generics/)
* [Writing an NES emulator: Part 1 - The 6502 CPU](https://analog-hors.github.io/site/pones-p1/)
* [ESP32 Embedded Rust at the HAL: GPIO Button Controlled Blinking](https://apollolabsblog.hashnode.dev/esp32-embedded-rust-at-the-hal-gpio-button-controlled-blinking?ref=twitter-share)
* [video] [A Practical Introduction to Declarative Macros in Rust](https://www.youtube.com/watch?v=dHv8FhcAl5U)

### Research

### Miscellaneous

* [Console #154 - An Interview with Giuliano of Sniffnet - Rust app to easily monitor network traffic](https://console.substack.com/p/console-154#§sniffnet)
* [DE] [Programmiersprache: Rust Foundation überarbeitet Trademark-Entwurf](https://www.heise.de/news/Programmiersprache-Rust-Foundation-ueberarbeitet-Trademark-Entwurf-8969427.html)

## Crate of the Week

<!-- COTW goes here -->

[Please submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## Call for Participation

Always wanted to contribute to open-source projects but did not know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

* [Hyperswitch - add `upsert` endpoint to `cards_info` table](https://github.com/juspay/hyperswitch/issues/994)
* [Hyperswitch - add a route that will invalidate cache](https://github.com/juspay/hyperswitch/issues/995)
* [Hyperswitch - Implement `ApiKeyInterface` for `MockDb`](https://github.com/juspay/hyperswitch/issues/996)
* [Hyperswitch - Implement `ConfigInterface` for `MockDb`](https://github.com/juspay/hyperswitch/issues/997)
* [velo - Add ability to switch canvas background - Issue #22 - StaffEngineer/velo - GitHub 3](https://github.com/StaffEngineer/velo/issues/22)
* [velo - Hex color widget - Issue #58 - StaffEngineer/velo - GitHub 1](https://github.com/StaffEngineer/velo/issues/58)
* [ockam - Update CLI documentation for `secure-channel-listener` commands 1](https://github.com/build-trust/ockam/issues/4774)
* [ockam - Update CLI documentation for `identity` commands](https://github.com/build-trust/ockam/issues/4777)
* [ockam - Refactor auto-reconnect replacer 1](https://github.com/build-trust/ockam/issues/4789)

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines].

[guidelines]: https://users.rust-lang.org/t/twir-call-for-participation/4821

## Updates from the Rust Project

<!-- Rust updates go here -->

### Rust Compiler Performance Triage

<!-- Perf results go here -->

### [Approved RFCs](https://github.com/rust-lang/rfcs/commits/master)

Changes to Rust follow the Rust [RFC (request for comments) process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

* [RFC: result_ffi_guarantees](https://github.com/rust-lang/rfcs/pull/3391)

### Final Comment Period

Every week, [the team](https://www.rust-lang.org/team.html) announces the 'final comment period' for RFCs and key PRs
which are reaching a decision. Express your opinions now.

#### [RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)

* [Add RFC on governance, establishing the Leadership Council](https://github.com/rust-lang/rfcs/pull/3392)

#### [Tracking Issues & PRs](https://github.com/rust-lang/rust/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* [disposition: merge] [Use fulfillment to check Drop impl compatibility](https://github.com/rust-lang/rust/pull/110577)
* [disposition: merge] [Only check outlives goals on impl compared to trait](https://github.com/rust-lang/rust/pull/109356)
* [disposition: merge] [rustdoc: restructure type search engine to pick-and-use IDs](https://github.com/rust-lang/rust/pull/110371)
* [disposition: merge] [Stabilize raw-dylib, link_ordinal, import_name_type and -Cdlltool](https://github.com/rust-lang/rust/pull/109677)
* [disposition: merge] [Add deployment-target --print flag for Apple targets](https://github.com/rust-lang/rust/pull/105354)

### [New and Updated RFCs](https://github.com/rust-lang/rfcs/pulls)
* [new] [RFC: Rustdoc configuration via Cargo (includes feature descriptions)](https://github.com/rust-lang/rfcs/pull/3421)
* [new] [RFC: Partial Types](https://github.com/rust-lang/rfcs/pull/3420)

### [Call for Testing](https://github.com/rust-lang/rfcs/issues?q=label%3Acall-for-testing)
An important step for RFC implementation is for people to experiment with the
implementation and give feedback, especially before stabilization.  The following
RFCs would benefit from user testing before moving forward:

* *No RFCs issued a call for testing this week.*

If you are a feature implementer and would like your RFC to appear on the above list, add the new `call-for-testing`
label to your RFC along with a comment providing testing instructions and/or guidance on which aspect(s) of the feature
need testing.

## Upcoming Events

Rusty Events between 2023-04-26 - 2023-05-24 🦀

### Virtual

* 2023-04-26 | Virtual (Cardiff, UK) | [Rust and C++ Cardiff](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/)
    * [**Rust-friendly websites and web apps**](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/events/292559177/)
* 2023-04-27 | Virtual (Charlottesville, VA, US) | [Charlottesville Rust Meetup](https://www.meetup.com/charlottesville-rust-meetup/)
    * [**Testing Tock, how unit tests in Rust improve and teach**](https://www.meetup.com/charlottesville-rust-meetup/events/292193436/)
* 2023-04-27 | Copenhagen, DK | [Copenhagen Rust Community](https://www.meetup.com/copenhagen-rust-community)
    * [**Rust meetup #35 at Google Cloud**](https://www.meetup.com/copenhagen-rust-community/events/292424926/)
* 2023-04-29 | Virtual (Nürnberg, DE) | [Rust Nuremberg](https://www.meetup.com/rust-noris/)
    * [**Deep Dive Session 3: Protohackers Exercises Mob Coding (as far as we get)**](https://www.meetup.com/rust-noris/events/292149688/)
* 2023-05-02 | Virtual (Buffalo, NY, US) | [Buffalo Rust Meetup](https://www.meetup.com/buffalo-rust-meetup/)
    * [**Buffalo Rust User Group, First Tuesdays**](https://www.meetup.com/buffalo-rust-meetup/events/lsjbbtyfchbdb/)
* 2023-05-03 | Virtual (Indianapolis, IN, US) | [Indy Rust](https://www.meetup.com/indyrs)
    * [**Indy.rs - with Social Distancing**](https://www.meetup.com/indyrs/events/qwtdjsyfchbfb/)
* 2023-05-09 | Virtual (Dallas, TX, US) | [Dallas Rust](https://www.meetup.com/dallas-rust/)
    * [**Second Tuesday**](https://www.meetup.com/dallas-rust/events/vndgwsyfchbmb/)
* 2023-05-11 | Virtual (Nürnberg, DE) | [Rust Nuremberg](https://www.meetup.com/rust-noris/)
    * [**Rust Nürnberg online**](https://www.meetup.com/rust-noris/events/gmkpctyfchbpb/)
* 2023-05-13 | Virtual | [Rust GameDev](https://discord.gg/yNtPTb2)
    * [**Rust GameDev Monthly Meetup**](https://discord.gg/yNtPTb2)
* 2023-05-16 | Virtual (Washington, DC, US) | [Rust DC](https://www.meetup.com/rustdc/)
    * [**Mid-month Rustful**](https://www.meetup.com/rustdc/events/jkxsctyfchbvb/)
* 2023-05-17 | Virtual (Cardiff, UK) | [Rust and C++ Cardiff](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/)
    * [**Rust Atomics and Locks Book Club Chapter 2**](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/events/292847157/)
* 2023-05-17 | Virtual (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust/)
    * [**Rust Study/Hack/Hang-out**](https://www.meetup.com/vancouver-rust/events/lqkkctyfchbwb/)

### Asia

* 2023-05-06 | Kyoto, JP | [Kansai Rust](https://www.meetup.com/kansai-rust/)
   * [**Rust Talk: Vec, arrays, and slices**](https://www.meetup.com/kansai-rust/events/293010553/)

### Europe

* 2023-04-26 | London, UK | [Rust London User Group](https://www.meetup.com/rust-london-user-group/)
    * [**Rust Hack & Learn April 2023**](https://www.meetup.com/rust-london-user-group/events/292729308/)
* 2023-04-27 | Bordeaux, FR | [DedoTalk](https://www.meetup.com/dedotalk/)
    * [**#2 DedoTalk 🎙️ : Comment tester son code Rust?**](https://www.meetup.com/dedotalk/events/292842782/)
* 2023-04-27 | Vienna, AT | [Rust Vienna](https://www.meetup.com/rust-vienna)
    * [**Rust Vienna - April - Hosted by Sentry**](https://www.meetup.com/rust-vienna/events/292751465/)
* 2023-05-02 | Amsterdam, NL | [Rust Developers Amsterdam Group](https://www.meetup.com/rust-amsterdam-group/)
    * [**Fiberplane Rust Workshop**](https://www.meetup.com/rust-amsterdam-group/events/292297784/)
* 2023-05-10 | Amsterdam, NL | [RustNL](https://rustnl.org/)
    * [**RustNL 2023**](https://2023.rustnl.org/)
* 2023-05-19 | Stuttgart, DE | [Rust Community Stuttgart](https://www.meetup.com/rust-community-stuttgart)
    * [**OnSite Meeting**](https://www.meetup.com/rust-community-stuttgart/events/pdhvctyfchbzb/)

### North America

* 2023-04-29 | Durham, NC, US | [Triangle Rust](https://www.meetup.com/triangle-rust/)
    * [**Rust Social / Coffee Chat at Boxyard RTP**](https://www.meetup.com/triangle-rust/events/292833711/)
* 2023-05-03 | Austin, TX, US | [Rust ATX](https://www.meetup.com/rust-atx/)
    * [**Rust Lunch**](https://www.meetup.com/rust-atx/events/293007744/)
* 2023-05-11 | Lehi, UT, US | [Utah Rust](https://www.meetup.com/utah-rust/)
    * [**Upcoming Event**](https://www.meetup.com/utah-rust/events/rrwbctyfchbpb/)
* 2023-05-16 | San Francisco, CA, US | [San Francisco Rust Study Group](https://www.meetup.com/san-francisco-rust-study-group/)
    * [**Rust Hacking in Person**](https://www.meetup.com/san-francisco-rust-study-group/events/vwljctyfchbvb/)

### Oceania

* 2023-04-27 | Brisbane, QLD, AU | [Rust Brisbane](https://www.meetup.com/rust-brisbane/)
    * [**April Meetup**](https://www.meetup.com/rust-brisbane/events/292965270/)
* 2023-05-03 | Christchurch, NZ | [Christchurch Rust Meetup Group](https://www.meetup.com/christchurch-rustlang-meetup-group/)
    * [**Christchurch Rust meetup meeting**](https://www.meetup.com/christchurch-rustlang-meetup-group/events/292993051/)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

## Jobs
<!--

Rust Jobs:

TWiR has stopped featuring individual job postings. You can read more about this change here:

https://github.com/rust-lang/this-week-in-rust/issues/3412

-->

Please see the latest [Who's Hiring thread on r/rust](INSERT_LINK_HERE)

# Quote of the Week

<!-- QOTW goes here -->

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nellshamrell](https://github.com/nellshamrell), [llogiq](https://github.com/llogiq), [cdmistman](https://github.com/cdmistman), [ericseppanen](https://github.com/ericseppanen), [extrawurst](https://github.com/extrawurst), [andrewpollack](https://github.com/andrewpollack), [U007D](https://github.com/U007D), [kolharsam](https://github.com/kolharsam), [joelmarcey](https://github.com/joelmarcey), [mariannegoldin](https://github.com/mariannegoldin), [bennyvasquez](https://github.com/bennyvasquez).*

*Email list hosting is sponsored by [The Rust Foundation](https://foundation.rust-lang.org/)*

<small>[Discuss on r/rust](REDDIT_LINK_HERE)</small>