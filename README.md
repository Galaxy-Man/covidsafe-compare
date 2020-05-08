# COVIDsafe Compare

On 8 May 2020 the Australian Government released the source code to its COVIDsafe mobile apps: https://github.com/AU-COVIDsafe/

This is a very very simple comparison between the relevant portions of the COVIDsafe iOS app and the OpenTrace community reference implementation: http://github.com/opentrace-community

**Warning! This is a very quick and dirty comparison and does not represent an in-depth analysis. I've written this README before even viewing the results, so it may end up being very uninteresting, but its presented in raw form for you to draw your own conclusions.**

## How this works

The `opentrace` branch of this repository is the [opentrace-ios](http://github.com/opentrace-community/opentrace-ios) implementation of its BlueTrace protocol found in [OpenTrace/Bluetrace](OpenTrace/Bluetrace).

The `covidsafe` branch of this repository is the [COVIDsafe iOS](https://github.com/AU-COVIDsafe/mobile-ios) implementation of the same code, found by comparing file names and type names.

The files from both apps were consolidated into a single directory.

You can find a single Pull Request on this repository. View the changed files there to see a standard diff between the two implementations.

Or just jump straight there: https://github.com/bok-/covidsafe-compare/pull/1/files

Feel free to leave comments!