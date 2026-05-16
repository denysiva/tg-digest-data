# tg-digest-data

Private digest input store for tg-digest-v2 cloud routine.
Daily JSON pushed by VPS nightly_collect.sh. Sanitization layer in prepare_digest_input.py strips t.me/c/ links, phones, emails, and excludes private chats.
