# What is Multihoming?

In an attempt to write a functional specification of what we want ChuuniIRC to
be, we found it impossible without describing multihoming itself. That is, we
do not believe multihoming to be an implementation detail of ChuuniIRC, but
rather, multihoming itself is the intended experience.

# What does multihoming feel like?

The initial experience of multihoming is not much different from traditional
social networks: you make an account, you talk to ppl. Where it differs is what
the network expects of you. For starters, you will find you have a lot less ppl
to talk to, or so it'll seem: Your first experience will be that your account
can only talk to a few handfuls of other ppl.

You notice these ppl talking about things of your interest, but you don't see
the full conversation yet. So, you decide to join their network, and make a new
account. Here, unlike traditional social networks, you are given the option to
join your new account with your old account, and can see and interact with both
networks. And you can keep doing this, expanding the networks you have access
to. This is the core multihoming experience.

In the eventual case an admin decides to delete one of your accounts, for
example as part of shutting down their network, they can only delete the one on
their network, and not any of your joined accounts. And, thanks to multihoming,
you're not relying on any single account to stay in touch with your friends.

# Interactions with Federation

Multihoming is, by itself, completely unrelated to federation. However, when
combined with federation, it can significantly improve the experience.
