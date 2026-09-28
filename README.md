# Developer tools and workflow-review resources


## ActionKit: free GitHub Actions review


[Open the free browser reviewer](https://actionkit-workflow-review.jvvkmusic.chatgpt.site) to inspect a workflow before you merge it. It highlights human-review prompts around permissions, action references, timeout limits, checkout scope, concurrency, and installation commands.


The browser review does not modify, execute, or upload a workflow. It is not a security audit or deployment approval.


## Free examples


[ActionKit workflow review examples](https://github.com/JVVK-AI/actionkit-workflow-review-examples) contains one deliberately synthetic GitHub Actions workflow for practice, along with the review boundaries.


## Optional local kit


The free reviewer also links to an optional **9 USDC** local kit with offline command-line review, batch reports, and handoff templates. The paid kit is separate from the public examples.

## GitHub Action and scoped reviews

[ActionKit workflow review action](https://github.com/JVVK-AI/actionkit-workflow-review-action) runs the same narrow prompts in GitHub Actions and writes a Markdown report to the job summary. For a public workflow that needs a bounded, separately scoped review or handoff, use the [workflow-review request form](https://github.com/JVVK-AI/actionkit-workflow-review-action/issues/new?template=workflow-review-request.yml). Scope, acceptance criteria, and price are agreed before work starts; do not share credentials, private repository links, or confidential code.



## Spreadsheet automation template

[Daily Spreadsheet Digest](https://github.com/JVVK-AI/daily-spreadsheet-digest) is a Google Apps Script template for one daily email summary from a selected Google Sheet tab. The owner configures the recipients and schedule in their own Google account; the repository contains only synthetic sample data. Teams that need a different source, schedule, approval step, or delivery channel can [request a separately scoped setup](https://github.com/JVVK-AI/daily-spreadsheet-digest/issues/new/choose) without sharing credentials or private documents.
