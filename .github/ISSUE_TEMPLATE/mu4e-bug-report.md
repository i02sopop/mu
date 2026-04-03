---
name: Mu4e Bug Report
about: Create a report to help us improve mu4e
title: "[mu4e bug]"
labels: bug, mu4e, new
assignees: ''
---

**Describe the bug**

Give the bug a good title.

Please provide a clear and concise description of what you expected to happen
and what actually happened, and follow the steps below.

**How to Reproduce**

Include the exact steps of what you were doing (commands executed etc.). Include
any relevant logs and outputs:

- Best start from `emacs -Q`, and load a minimal `mu4e` setup; describe the steps
  that lead up to the bug.
- Does the problem happen each time? Sometimes?

- Try some small variations of what you were doing. Does it make a difference?

- If this is about a specific (kind of) message, attach an example message.
  (Open the message, use `M-x mu4e-copy-message-path` and open the message file,
  truncate/anonymize as needed (as long as the issue still reproduces), and
  attach to the ticket.

- Include relevant versions of software and/or other specifics of your system
  that may be relevant.

**Environment**

Please describe the versions of OS, Emacs, mu/mu4e etc. you are using.

**Checklist**

- [ ] you are running either an 1.12.x/1.14.x release or `master` (otherwise please upgrade)
- [ ] you can reproduce the problem *without* 3rd party extensions (including
      Doom/Evil, various extensions etc.)
- [ ] you have read all of the above

Please make sure you all items in the checklist are set/met before filing the ticket.

Thank you!
