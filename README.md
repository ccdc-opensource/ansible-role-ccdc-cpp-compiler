# Ansible Role: Install C++ compilers

Install C++ compilers for various platforms.

Applying this role will set up appropriate C++ compilers and base system requirements for each platform on the target machine.

### Linux

-   devtoolset-10 (CentOS)
-   build-essential (Debian)

### macOS

-   XCode

### Windows

-   Visual Studio 2019 VC Tools
-   Visual Studio 2010 Remote Tools

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ccdc.cpp_compiler

## License

MIT / BSD

## Author Information

This role was created in 2020 by Claudio Bantaloukas, based on existing roles at CCDC, by Jeff Geerling and google searches
