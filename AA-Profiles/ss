include <tunables/global>

# vim:syntax=apparmor
# AppArmor policy for ss

# ------------------------------------------------------------------
#
#    Copyright (C) 2024 privateboss01
#
#    This program is free software; you can redistribute it and/or
#    modify it under the terms of version 2 of the GNU General Public
#    License published by the Free Software Foundation.
#
# ------------------------------------------------------------------


/usr/bin/ss {
  include <abstractions/base>
  include <abstractions/nameservice>

  /proc/*/net/udp r,
  /proc/*/net/udp6 r,

}
