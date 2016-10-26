## ansible-perl - [![Build Status](https://travis-ci.org/grimmjow8/ansible-role-ffmpeg.png?branch=master)](https://travis-ci.org/grimmjow8/ansible-role-ffmpeg)

Ansible role: ffmpeg
====================

Installs ffmpeg build by [John Van Sickle](http://johnvansickle.com/) on any Linux or UNIX system.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`)

```yml
# temp working directory
ffmpeg_temp_path: "/tmp/ffmpeg"

# ffmpeg executable path
ffmpeg_exe_path: "/usr/bin/ffmpeg"

# ffprobe executable path
ffprobe_exe_path: "/usr/bin/ffprobe"

# ffmpeg version
ffmpeg_version: "3.1.5"
```

Dependencies
------------

None.

Example Playbook
----------------
```yml
- hosts: servers
  roles:
    - grimmjow8.ansible-role-ffmpeg
```

License
-------

MIT

Author Information
------------------

[Hedi Chaibi](https://hedichaibi.com)
