# [PROJECT] RFC

The "RFC" (Request for Comments) process is designed to ensure a structured and transparent approach for introducing significant changes to the [PROJECT]. It allows all stakeholders to review, discuss, and align on the proposed features, ensuring confidence in the project's direction.

[Active RFC List](https://github.com/bravonatalie/rfcs/pulls)

## What the process is

In short, to get a major feature added to [PROJECT], one usually first gets
the RFC merged into the RFC repo as a markdown file. At that point the RFC
is 'active' and may be implemented with the goal of eventual inclusion
into [PROJECT].

- Create a new branch
- Copy `0000-template.md` to `text/0000-my-feature.md` (where "my-feature" is descriptive). Don't assign an RFC number yet; This is going to be the PR number and we'll rename the file accordingly if the RFC is accepted.
- Fill in the RFC. Put care into the details: RFCs that do not present convincing motivation, demonstrate lack of understanding of the design's impact, or are disingenuous about the drawbacks or alternatives tend to be poorly-received.
- Submit a pull request. As a pull request the RFC will receive design
  feedback from others contributors, and the author should be prepared
  to revise it in response.

- Now that your RFC has an open pull request, use the issue number of the PR to rename the file: update your 0000- prefix to that number.

- An RFC can be modified based upon feedback from the team.

- An RFC may be rejected by the team after discussion has settled
  and comments have been made summarizing the rationale for rejection. A member of
  the team should then close the RFCs associated pull request.

- An RFC may be accepted and a team member will merge the RFCs associated pull request, at which point the RFC will become 'active'.

<br>

**This RFC process owes its inspiration to the [Yarn RFC process] and [Rust RFC process]**

[Rust RFC process]: https://github.com/rust-lang/rfcs
[Yarn RFC process]: https://github.com/yarnpkg/rfcs
