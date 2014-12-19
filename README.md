# Service Contracts
This aims to be a legally defensible fork of Daniel Beardsley's [Service
Contracts](https://github.com/danielbeardsley/service_contracts) project, a
collection of simple and relatively generic service contracts for the Design /
Development crowd.  It's necessary because he's only interested in
[readability, not legal
defensibility](https://github.com/danielbeardsley/service_contracts/pull/3).

The authoritative fork is maintained on
[GitLab](https://gitlab.com/colan/service_contracts_legal).  Please open any
tickets or merge requests over there.  A mirror is maintained on
[GitHub](https://github.com/colans/service_contracts) for convenience.

## How To Use
1. Clone the repository locally.
2. Create a non-public branch for each client and fill in the details: names,
rates, specific terms, ...
	* Send the contract back and forth in plain text or use Google Documents
	  until the terms have been finalized.
3. Convert the Markdown to HTML with something like [Formattr](http://formattr.heroku.com)
4. Then add something like: "contract id: 87ffdsf4" to the footer with the
	 first 8 characters of the commit id that represents the final contract.
5. Create a PDF of the document with your signature and send it to the client.

## Contributions
You are free to fork away and issue pull-requests.


Licensed under the MIT license: http://www.opensource.org/licenses/mit-license.php
