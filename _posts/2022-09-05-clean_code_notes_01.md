---
layout: post
title: notes_chapter_one_art_of_clean_code
description: "Some notes from Chapter 1 of 'THE ART OF CLEAN CODE' by Christian Mayer"
---

## Step one is acknowledging you can write more consumable code.
## Step two is prioritizing writing code for humans, not computers.
## Step three is ensuring your code is consistently written in this way.

As a developer, the reality in 2022 is that no one is doing anything new in most modern languages.

Assuming this to be true what can one even do to improve the work you output?

We can explicitly take steps to reduce the complexity of our code, for both machines and humans to process.

We should prefer clarity in the former unless requirements dictate otherwise.

### Complexity

| Complexity | Description |
| ---------- | ----------- |
| Algorithmic | How much resources does your codebase consume at runtime, this is also sometimes referred to as time complexity. |
| Cyclomatic | How many possible outcomes does your codebase produce, how many branching paths are there before the expected output is produced? |
| Cognitive | How difficult is your codebase to understand, did you use sorted() or write an entirely new module to run a radix sort because you felt like it? |

I urge us to look up best practices and stick to them, possibly even introduce some of the common tools such as black(code style formatter for python) and pylint(linter and formatter for python) into your workflow.

We should review known antipatterns before calling our problems solved, thankfully pylint can catch some of these when used correctly with a reasonable false positive rate.

### Links

Source: [https://nostarch.com/art-clean-code](https://nostarch.com/art-clean-code)

Pylint: [https://pylint.pycqa.org/en/latest/](https://pylint.pycqa.org/en/latest/)

Black: [https://black.readthedocs.io/en/stable/](https://black.readthedocs.io/en/stable/)
