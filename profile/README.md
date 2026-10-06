# pLabs5

homebrew and research for the playstation 5.

> [!WARNING]
> I, foxinwinter and any other contributers to this organization
> are not responsible for any damages 
> or consequences directly or indirectly caused by any
> software under this organization.

## projects

| project | what it is | state |
|---|---|---|
| [pWeb5](https://github.com/pLabs5/pWeb5) | jailbreak autoloader that runs in the console's own browser | live |
| [dRPC5](https://github.com/pLabs5/dRPC5) | discord rich presence, straight from the console | usable |
| [yFree5](https://github.com/pLabs5/yFree5) | homebrew Youtube Client for the PS5 with no Ads | in progress, early developement |
| [pYTM5](https://github.com/pLabs5/pYTM5) | future planned Youtube Music client for the PS5  | not started/ planned|

## pWeb5

a jailbreak autoloader that runs inside the console's browser. it executes the
exploit chain in the page, shows you what it is doing while it does it, then
pushes homebrew payloads once the chain is up.

live at <https://pweb5.pages.dev>. firmware 7.00 through 13.60.

the chain is a rework of Relapse that verifies each step instead of assuming it
worked.

## dRPC5

a payload that publishes discord rich presence straight from the console. it
connects to the gateway on its own, so there is no pc host or bridge sitting in
the middle.

it identifies as a console session, so the account shows up as active on
playstation 5.

this one uses a self-bot style approach with a user token. that is against the
discord terms of service, and while it is rarely enforced, that is your call to
make.

## yFree5

a homebrew video player. it does its own rendering, input, and networking, and
ships a few small helper payloads alongside the main one for network discovery
and probing.

still being built. expect things to move around.

## pYTM5

research notes, not code yet. the goal is a music player for youtube music and
other streaming sources that registers with the console's system music playback
widget, so it shows up in the music card and the control center next to spotify
and apple music.

most of the audio side is already public. the README keeps what has been worked
out so it does not have to be worked out again.


## Legal

I, foxinwinter/pLabs5, as well as its contributers, are not affiliated with, associated with, sponsored by,
endorsed by, otherwise established with Sony Interactive Entertainment, Playstation, Discord, or any of their
other companies or works unless explictly stated otherwise.
Just because a explict mention above isn't present does **NOT** mean otherwise.

All software is provided "as is", without warranty of **ANY** kind, express
or implied. Use all software at your own risk.

You are solely responsible for complying with terms of service of all programs, as
well as any applicable law. 
