Install and configure Jellyfin
=========

The role installs and configures Jellyfin for my server.

Role Variables
--------------

The ```jellyfin_ffmpeg_version``` can be set to the jellyfin ffmpeg version from <https://repo.jellyfin.org/releases/server/debian/versions/jellyfin-ffmpeg>

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - { role: ansible-jellyfin, jellyfin_ffmpeg_version: 6.0-8 }
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
