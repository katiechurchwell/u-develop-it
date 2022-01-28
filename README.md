# U Develop It :ballot_box_with_check:
  [![project-languages-used](https://img.shields.io/github/languages/count/katiechurchwell/u-develop-it?color=important)](https://github.com/katiechurchwell/u-develop-it)
  [![project-top-language](https://img.shields.io/github/languages/top/katiechurchwell/u-develop-it?color=blueviolet)](https://github.com/katiechurchwell/u-develop-it)

## Summary
Back end for U Vote It, a voting application for developer meetup group called U Develop It. This was made as an exercise in storing structured data in a relational database and using the MySQL command-line interface.

## Description
The election database consists of 3 tables: candidates, parties and voters. Users are able to submit votes for the candidate of their choosing and on the backend we are able to look at when that vote was cast as well as some additional information about them.

Additionally our candidates are tied to one of three parties and we establish that through a foreign key.

This code is modularized and uses prepared statements & error handling.
