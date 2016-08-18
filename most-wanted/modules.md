# Most Wanted Modules

These are the most-wanted pure Perl 6 modules (as opposed to
[native library bindings](bindings.md)).  These may be direct ports of Perl 5
libraries, but that is not necessarily the case.

## WIP Tags

If you start implementing a module, but it's not ready for the release to the
public yet, please mark it in the list as WIP (Work In Progress) with a link
to the repository, so other potential authors do not assume no one is working
on this problem.

Once your work is added to the ecosystem, please **remove it from the Most
Wanted list,** even if you're still fleshing out the module.

## Configuration

* GitLike

## Cryptography and security

* Crypto
  + GPG
  + Block cyphers
    - DES
    - Blowfish
    - Twofish
  + Full set of block cypher modes

## Data formats

* Archives
  + Tar (WIP: [Archive::Tar](https://github.com/FROGGS/p6-Archive-Tar))
* Textual interchange of structured data
  + LDIF
      - Net::LDAP port
* File metadata
  + Image::Exiftool
* XML-based formats
  + RSS/Atom

## Data processing

* Data::Visito
* Deep::Clone

## Databases

* DBM?
* NoSQL
  + CouchDB (WIP: [Sofa](https://github.com/jonathanstowe/Sofa))
* CHI, Cache::Cache, or similar
* LDAP
  + Net::LDAP port?


## Development

* Corelist
* Ecosystem
  + File::ShareDir
  + Pod::Cpandoc
  + App::cpanoutdated (equivalent for panda)
* App::Grindperl
* Debugging (WIP: [Rakudo::Debugger](https://github.com/jnthn/rakudo-debugger/))
  + Carp::REPL
  + Devel::FindRef
  + Devel::PartialDump
* Tracing
  + Devel::STDERR::Indent
* Profiling
  + Devel::NYTProf?
* Tidying
  * Perl::Tidy
  * Code::TidyAll
* Editor/IDE interfaces
  + Proc::InvokeEditor
  + Vi::QuickFix?
* Project lifecycle
  + Dist::Zilla
  + CPAN::Uploader
* Deployment
  + Carton
  + cpanfile
  + Pinto


## Filesystems

* File::Spec (WIP: [File::Spec](https://github.com/FROGGS/p6-File-Spec/))
* File::pushd (WIP: [File::pushd](https://github.com/Emeric54/File-pushd))


## i18n and NLP

Internationalization and Natural Language Processing

* App::Uni
* Unicode::Collate?
* Unicode::UCD?
* Unicode::Tussle?
* Unicode::LineBreak?
* Encodings/charsets other than builtin UTF-8/Unicode
* Maketext
* Standard codes:
  + country
  + currency
  + language
  + script
* Lingua::Stem::*


## IPC

* IPC::Cmd
* DBus via [sd-bus](http://0pointer.net/blog/the-new-sd-bus-api-of-systemd.html)
* Device::SerialPort


## Logging

* pluggable logging
  + Windows logging
  + file/handle


## Networking

* Email
  + Email::Sender
  + Mime::Lite
* HTTP
  + RobotUA?
  + OAuth
* RPC
  + JSON-RPC (WIP: [JSON::RPC](https://github.com/bbkr/jsonrpc/))
  + SOAP
  + XML-RPC?
* IRC
  + IRC::Utils (WIP: [IRC::Utils](https://github.com/soh-cah-toa/p6-irc-utils/))
* Other protocols
  + NNTP
  + Ping
  + Telnet
* Internet services
  + Net::GitHub::V3
  + App::ph
* Security
  + Mozilla::CA


## Numerical

* Geo::Ellipsoid (WIP: [Geo::Ellipsoid](https://github.com/tbrowder/Geo-Ellipsoid-perl6))


## Text processing

* Regex/Grammar utilities
  + Regexp::Common


## Testing

* Smoking and reporting
  + Test::Reporter
  + CPANTS
* Harnesses
  + TAP::Parser
  + App::Prove
  + App::ForkProve
  + Test::Aggregate?
* Test output
  + Test::Differences
  + Test::Deep
  + Test::Pretty?
* Completeness
  + Code coverage
* Specific tests
  + Test::Requires
  + Test::Spelling
  + Test::Number::Delta (WIP: [Test::Number::Delta](https://github.com/tbrowder/Test-Number-Delta-perl6/))
* Simulation
  + Test::Without::Module


## Unix

* IO::Select (WIP: [IO::Select](https://github.com/tadzik/IO-Select/))
* IO::Pty/IO::Pty::Easy
* open2/open3
* shared mem
* Fcntl
* POSIX
* Daemonize


## User interfaces

* Command line
  + Term::UI?
* Terminal
  + Term::Cap  (WIP: [Term::Cap](https://github.com/jonathanstowe/p6-Term-Cap))
  + Term::Complete
  + Term::ReadLine
  + App::Ttyrec?
  + App::Termcast?
  + Term::KBD
* Plotting/Charting/Graphing
  + Chart::Clicker
* GUI
  + WxWidgets


## Utilities

* App::Ack
* Email::Filter
