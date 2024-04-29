<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-pro/iam-ssh/blob/master/lib/files/iam-ssh-cli/lib/iam_ssh/help/completion.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

## Examples

    iam-ssh completion

Prints words for TAB auto-completion.

    iam-ssh completion
    iam-ssh completion hello
    iam-ssh completion hello name

To enable, TAB auto-completion add the following to your profile:

    eval $(iam-ssh completion_script)

Auto-completion example usage:

    iam-ssh [TAB]
    iam-ssh hello [TAB]
    iam-ssh hello name [TAB]
    iam-ssh hello name --[TAB]
