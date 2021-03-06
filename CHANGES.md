Change log for the Test::Deeply::Relaxed Raku module
====================================================

0.1.3
-----

- Rename the files using Raku extensions.
- Add some more fields to the META6.json file.

0.1.2
-----

- Move the "use v6.c" declaration to the first lines of
  all files that it appears in; thanks, Aleks-Daniel
  Jakimenko-Aleksejev!
- Add a .gitignore file.
- Test with more recent Perl 6 versions.

0.1.1
-----

- Add the 06-meta test to test META6.json.
- Add some magic to .travis.yml to get Travis CI to install
  all the needed dependencies with both zef and panda.
- Test the 2017.{06,07,08,09} releases with Travis CI.
- Use the set operators for baggy tests, too, instead of
  the deprecated bag operators.  Closes: #2
- No longer test with Panda on Travis CI.
- Merge Samantha McVey's pull request #1 to specify
  the Artistic-2.0 license in META6.json.

0.1.0
-----

Initial public release.
