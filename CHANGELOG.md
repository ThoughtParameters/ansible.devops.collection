# Thoughtparametersllc\.Devops Release Notes

**Topics**

- <a href="#v0-0-2">v0\.0\.2</a>
    - <a href="#release-summary">Release Summary</a>
    - <a href="#minor-changes">Minor Changes</a>
- <a href="#v0-0-1">v0\.0\.1</a>
    - <a href="#release-summary-1">Release Summary</a>
    - <a href="#major-changes">Major Changes</a>
    - <a href="#minor-changes-1">Minor Changes</a>
    - <a href="#breaking-changes--porting-guide">Breaking Changes / Porting Guide</a>
    - <a href="#deprecated-features">Deprecated Features</a>
    - <a href="#removed-features-previously-deprecated">Removed Features \(previously deprecated\)</a>
    - <a href="#security-fixes">Security Fixes</a>
    - <a href="#bugfixes">Bugfixes</a>
    - <a href="#known-issues">Known Issues</a>

<a id="v0-0-2"></a>
## v0\.0\.2

<a id="release-summary"></a>
### Release Summary

Updated the GitHub Actions workflow to use the GitHub release tarball \(already built and published in a GitHub Release\)
when publishing to Ansible Galaxy \(galaxy\.ansible\.com\)\, instead of rebuilding the collection artifact again\.

<a id="minor-changes"></a>
### Minor Changes

* GitHub Actions workflow \- use the existing release tarball from the GitHub Release to publish the collection to Ansible Galaxy\, reducing redundant builds and ensuring consistency\.

<a id="v0-0-1"></a>
## v0\.0\.1

<a id="release-summary-1"></a>
### Release Summary

Initial release of the ThoughtParameters\.Devops collection\.

<a id="major-changes"></a>
### Major Changes

* Added \.ansible\-lint configuration for better code quality\.
* Added initial collection files and structure\.
* Added license information and metadata\.
* Created comprehensive documentation and examples\.
* Documented collection usage and contribution guidelines in README\.md\.
* Established versioning strategy and release process\.
* Introduced changelog management using antsibull\-changelog\.
* Set up GitHub Actions for automated testing and releases\.
* Updated changelog/config\.yaml for customized changelog generation\.

<a id="minor-changes-1"></a>
### Minor Changes

<a id="breaking-changes--porting-guide"></a>
### Breaking Changes / Porting Guide

<a id="deprecated-features"></a>
### Deprecated Features

<a id="removed-features-previously-deprecated"></a>
### Removed Features \(previously deprecated\)

<a id="security-fixes"></a>
### Security Fixes

<a id="bugfixes"></a>
### Bugfixes

<a id="known-issues"></a>
### Known Issues

