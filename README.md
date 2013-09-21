pidgin-notifier
===============

A notification service for the Pidgin IM client. Pops up a visual notification
when designated substrings are mentioned in any conversation, or when there is
any activity in designated conversations.

Substrings and conversations can be designated for highlighting by placing them
in a JSON file - ~/.pidgin-notifier by default. The format of this file:

    {
        "texts": [
            "some designated",
            "case-insensitive substrings"
        ],
        "convs": [
            "some",
            "conversations"
        ]
    }

Requires DBus and GObject, tested on Linux.
