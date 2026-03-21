# user-mapping

Dynamically create a user with a specific UID and GID.

This Makejail is designed to be included in other Makejails that need to run a process as a non-root user, but with a specific user UID and GID. For this reason, the `puid` and `pgid` arguments have been implemented, with a default value of `1000`.
