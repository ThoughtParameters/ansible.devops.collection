=========================================
Thoughtparametersllc.Devops Release Notes
=========================================

.. contents:: Topics

v0.0.2
======

Release Summary
---------------

Updated the GitHub Actions workflow to use the GitHub release tarball (already built and published in a GitHub Release)
when publishing to Ansible Galaxy (galaxy.ansible.com), instead of rebuilding the collection artifact again.

Minor Changes
-------------

- GitHub Actions workflow - use the existing release tarball from the GitHub Release to publish the collection to Ansible Galaxy, reducing redundant builds and ensuring consistency.

v0.0.1
======

Release Summary
---------------

Initial release of the ThoughtParameters.Devops collection.

Major Changes
-------------

- Added .ansible-lint configuration for better code quality.
- Added initial collection files and structure.
- Added license information and metadata.
- Created comprehensive documentation and examples.
- Documented collection usage and contribution guidelines in README.md.
- Established versioning strategy and release process.
- Introduced changelog management using antsibull-changelog.
- Set up GitHub Actions for automated testing and releases.
- Updated changelog/config.yaml for customized changelog generation.

Minor Changes
-------------

Breaking Changes / Porting Guide
--------------------------------

Deprecated Features
-------------------

Removed Features (previously deprecated)
----------------------------------------

Security Fixes
--------------

Bugfixes
--------

Known Issues
------------

