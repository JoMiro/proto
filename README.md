proto
=====

protobuffs tool

Build
-----

    $ rebar3 compile

Use
---

Add the plugin to your rebar config:

    {plugins, [
        { proto, ".*", {git, "git@host:user/proto.git", {tag, "0.1.0"}}}
    ]}.

Then just call your plugin directly in an existing application:


    $ rebar3 proto
    ===> Fetching proto
    ===> Compiling proto
    <Plugin Output>
