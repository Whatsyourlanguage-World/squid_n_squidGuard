# Useful Bash CMD's

## Extract config-lines without any comments or useless spaces . See .orig file for Help
cat squid.conf | grep -v ^"# " | grep -v ^"#.*$" | grep -v ^$
