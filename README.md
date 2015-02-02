#runscopetool

A tool that uses the Runscope API to run a specific test(s) on a specific
environment(s). It can either run the tests automatically, or it can generate a
URL that can be used as a webhook.

##Prerequisites
I use python to prettify the JSON output from curl calls.
I use ```jq``` to parse the JSON output.

To install with Homebrew:
```brew install jq```
