# Hell is other people's code

You probably depend on some open source code, but do you realize the potential risks of doing it?

Over 30% of all open source projects use a package manager to declare at least one dependency

The average open source ruby project has 50 dependencies and the average node.js project has over 150 dependencies on third party code. 

TODO **finish dependency counting research**

There are a number of things to consider when adopting a dependency into your application

## Dependencies

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
