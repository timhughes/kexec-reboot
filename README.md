# kexec-reboot



Usage: ./kexec-reboot: [-k kernel_version] [-c "command line args"] [-d]

  -k <string>          # kernel version in the format given by `uname -r`
  -c <string>          # kernel arguments. If not provided then will default to the current running kernel's args
  -d                   # dry-run, just print out what would happen
  -h                   # this help
