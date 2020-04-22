# nbdev template


nbdev project template.

Clone of https://github.com/fastai/nbdev_template.


A few files have been modified from master as of 2020-04-22:

- settings.ini - lightly modified to remove references to fastai
- setup.py - remove license details & license checking
- Delete LICENSE.
- In .github/workflows/main.yaml:
	- Disable tests
	- Disable nb diffs 	
	
 ... as these will both fail for the first run, and can be re-enabled later.


##### Using with existing code:

In general (WIP, not thoroughly tested:)

Copy all files here into the target directory. Update settings.ini with details.

You might see unusual behavior if your existing code is not in repo root. If you want to publish something on pypi, this may break things; better to start with a fresh copy of nbdev_template as your repo and copy your code into that.


