# Contributing

The SWHID specification is maintained by the [SWHID core team][swhid-core-team].
Coordination is primarily done via the team [mailing list][swhid-list] (see [how to join][howto-join]) and meetings.

### Workflow
Contributors open [issues][issues] on the specification repository, and when reasonable consensus emerge on how to address the issue, they create a [pull request][pull-requests] that implements it. Contributors may also open a pull request directly if they feel that it's more appropriate.

Discussion and collaboration on an issue or a pull request take place directly under the issue or pull request itself.

When the Maintainers determine that there is a consensus, the pull request is merged.

### Major Changes

Any change that breaks backwards compatibility or requires significant tooling changes is considered a major change. After you create the issue, you may want to call attention to it on [the mailing list][swhid-list] to get maximum feedback before investing time in a pull request.

### Minor Changes

Minor changes such as markup and typo fixes may be submitted directly to this repository as [pull requests][pull-requests] without previous discussion.

## Submitting changes

Always write a clear log message for your commits. One-line messages are fine for small changes, but significant changes should look like this:

    $ git commit -m "Subject of the commit
    >
    > One ore more paragraph(s) describing what changed and its impact."

A properly formed Git commit subject line should always be able to complete the following sentence: if applied, this commit will "Subject of the commit". For example :

    [if applied, this commit will] Add chapter on computing directory node hashes in SWHID
    [if applied, this commit will] Delete paragraph with outdated SWHID references
    [if applied, this commit will] Fix grammar in SWHID core identifier

Git itself uses this approach. When you merge something it will generate a commit message like "Merge branch...", or when reverting "Revert...".

## Contribution License

All contributions to the SWHID standard documents are submitted under the [Community Specification License 1.0](https://github.com/swhid/governance/blob/main/1._Community_Specification_License_1.0.md).
Contributions to companion software tools and libraries are submitted under the open source license indicated in the corresponding software projects and files.

By making a contribution to this project, you certify that the contribution was created in whole or in part by you and you have the right to submit it under the corresponding license.
You understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information you submit with it, including your sign-off) is maintained indefinitely and may be redistributed consistent with this project or the license(s) involved.

To certify that your contribution complies with the above contribution conditions, a `Signed-off-by` line like the following (replace with your own identity):

    Signed-off-by: Author Name authoremail@example.com

must be included in every commit message.
Changes made through the web interface include this line. If you use the command line, you can do this by passing the `-s` flag to `git commit`.

More information on the decision making process can be found in the [SWHID governance documents](https://github.com/swhid/governance/).

[issues]: https://github.com/swhid/specification/issues/
[pull-requests]: https://github.com/swhid/specification/pulls/
[swhid-list]: https://groups.google.com/g/swhid-discuss
[howto-join]: https://support.google.com/a/users/answer/9304806
[swhid-core-team]: https://swhid.github.io/coreteam
