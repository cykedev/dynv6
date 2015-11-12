# dynv6
Update script for dynv6.com to set your IPv4 address and IPv6 prefix

Small changes have been made in order to pass the API Token as an argument.

## usage
Can be calles via crontab:

    */5 * * * * /home/user/bin/dynv6.sh some-host.dynv6.net aabbccddeeffgghhiijjkkllmmnnoo >/dev/null 2>&1

where `aabbccddeeffgghhiijjkkllmmnnoo` is the API Token and `some-host.dynv6.net` is the DynV6 hostname.


See [this Gist](https://gist.github.com/corny/7a07f5ac901844bd20c9) for the original code.
