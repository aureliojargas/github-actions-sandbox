# GitHub Actions Sandbox

This is the repository where I learn/discover/debug how the GitHub CI works.

See the open pull requests. Each one is a different test case.

### References

* Docs: https://docs.github.com/en/actions/reference

* YAML file reference: https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions

* Runner: 
  * docs: https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners
  * code: https://github.com/actions/runner

* More details about the `shell` attribute and its customization:\
  https://github.com/actions/runner/blob/484ea74ed003bd3c80175cff0f69d1ff807bd8d7/docs/adrs/0277-run-action-shell-options.md

* Default arguments for each supported `shell`:\
  https://github.com/actions/runner/blob/be9632302ceef50bfb36ea998cea9c94c75e5d4d/src/Runner.Worker/Handlers/ScriptHandlerHelpers.cs#L14-L15

* VMs repository:\
  https://github.com/actions/virtual-environments

* Ubuntu-20.04 pre-installed software:\
  https://github.com/actions/runner-images/blob/main/images/linux/Ubuntu2004-Readme.md
