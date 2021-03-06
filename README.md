# Hell is other people's code

- 1. [Dependencies](#dependencies)
- 2. [Licensing](#licensing)
- 3. [Security](#security)
- 4. [Support](#support)
- 5. [Bus Factor](#bus-factor)
- 6. [Bitrot](#bitrot)
- 7. [Risk](#risk)
- 8. [Mitigation](#mitigation)

## Intro

You probably depend on some open source code, but do you realize the potential risks of doing it?

Over 30% of all open source projects use a package manager to declare at least one dependency

The average open source ruby project has 50 dependencies and the average node.js project has over 150 dependencies on third party code.

TODO **finish dependency counting research**

There are a number of things to consider when adopting a dependency into your application

## Dependencies

- "You don't download, or import, a software dependency, you adopt it. Like adopting pets, it's a responsibility for the life of your product." - https://twitter.com/davecheney/status/616931340466786304
- package managers
- transitive dependencies

## Licensing

- Unlicensed code
- Copyleft licenses
- Conflicting licenses
- Transitive licenses
- Non-Open Source Licenses (example: greensock)

## Security

- CVEs and NVD
- default configurations (elasticsearch localhost)
- There were 14,185 reported security vulnerabilities in 2015, that's an average of 38 per day

## Support

- Deprecated libraries
- Unmaintained libraries
- Dead libraries
- Unresponsive issue trackers
- Deleted/removed code

## Bus Factor

- How many people need to get hit by a bus to kill the project?
- Commit bit
- Github Admin rights
- Package manager publish bit


## Bitrot

- Software being "Done" is like lawn being "Mowed" - https://twitter.com/ourfounder/status/770075137332932608
- The gradual decay of working software
- parallax train animation
- OS -> system level dependencies -> application level dependencies -> application

## Risk

- unmaintained projects
- public facing
- personal data

## Mitigation

- shrinkwrapping
- vendoring
- automatic updating
