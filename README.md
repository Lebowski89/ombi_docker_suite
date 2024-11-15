Ombi Suite
=========

    Standalone Ansible role to automate the full set-up of Ombi - a media request app for Plex and Emby users.
      - Includes the installation of Docker (Debian-based distros) and Ansible dependencies within the role.
      - Includes the option of setting up and connecting Ombi to a Mariadb database.
      - Includes the option of creating a Cloudflare DNS record for your Ombi instance for reverse proxy purposes.
      - Includes the option of joining Ombi to an existing Traefik docker network (or creating one if none exists).

Docker containers included: ombi, mariadb

What this role is: First and foremost, this role has been crafted and designed to serve the needs of.. me.
However, when and where possible - the role has included toggles, conditionals, and tasks to improve compatiblity and usability.
This role is intended for someone who has ansible installed and wants to deploy these apps locally or onto a remote system.

Defining 'Standalone': This role is designed to deploy the above apps and their companions and nothing more. It includes all
required defaults/variables within the role, and is designed to get these apps up and running within a single role. It is not
designed to be a one-stop OS overhaul. Those needing maximum ease, compatibility, and a large support base should try Saltbox.
