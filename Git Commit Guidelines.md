# Git Commit Message Guideline

This is the official style guide to follow in my projects.


### Message Structure

A git commit message consists of three distinct parts separated by a blank line:
The title, an optional body and an optional footer.
A title consists of a descriptive tag, representing the type of the message, and the subject.

The layout is as follows:

<code>type: Subject
body
footer
</code>


### Type

The title of a commit message should contain one of the following descriptive tags:
- <code>feat</code>: 		A new feature
- <code>fix</code>: 		A bug fix
- <code>docs</code>: 		Changes to documentation
- <code>style</code>: 		Formatting, missing semi colons, etc; no code change
- <code>refactor</code>: 	Refactoring production code
- <code>test</code>: 		Adding tests, refactoring test; no production code change
- <code>chore</code>: 		Updating build tasks, package manager configs, etc; no production code change


### Subject

The subject should:
- be less than 50 characters
- begin with a capital letter
- end without a period
- use an imperative tone to describe what the commit does
- use simple present (i.e. 'change'; not 'changed' or 'changes')


### Body

The body:
- is uesed only when a commit is complex enough to require explanation
- explains what a commit does and why, not how
- requires a blank line between the title and the body!
- should be limited to 72 characters per line


### Footer

The footer is optional and is used to reference issue tracker IDs.


### Example Commit Message

<code>
feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
</code>
