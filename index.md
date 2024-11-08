# ChuuniIRC

ChuuniIRC is a new approach to social media, built with lessons learned from
ActivityPub.  Despite its name, ChuuniIRC is much deeper rooted in microblogging
than in instant messaging.

## Built for Multihoming

Multihoming is the ability for a client to make effective use of multiple
instances.  ChuuniIRC builds around multihoming to improve moderation and make
the network resilient to instance shutdowns.

Through easy discovery of connected accounts ("alts"), moderators can more
effectively do common moderation tasks that are notoriously difficult on other
federated networks.  Additionally, by connecting to multiple instances, should
an instance shut down, you don't lose your access to the network, and it's all
seamless!

## Inspired by Communities

Communities have multiple modes of interaction, ranging from an individual
participating in multiple, possibly overlapping, communities, up to multiple
communities and even groups of communities getting together as a whole.

If community-community interactions are represented by federation, then
individual-community interactions are represented by multihoming, and ChuuniIRC
supports both.

## Decentralized by Design

Unlike, say, Mastodon, ChuuniIRC is structured in such a way that the flagship
software is developed by the communities that use it.  There is no BDFL, and
forking is encouraged.

Consequently, development follows the values of the communities, including
features, default filters, easter eggs, etc.

## End-to-End Encryption (E2EE)

Unlike traditional social media, ChuuniIRC enforces end-to-end encryption of
direct messages.  ChuuniIRC also has a major advantage over other encrypted
networks: thanks to its strong focus on multihoming, it is much more resilient
to attacks against the E2EE layer - a single compromised instance can't redirect
the encryption nor cause a denial of service.

## Coming soon!

ChuuniIRC is not yet ready for a public release.  Watch this space!  In the mean
time, feel free to come by #chuuniirc on libera.chat.
