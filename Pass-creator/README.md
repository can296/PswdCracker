# CUPP - Common User Passwords Profiler

## About

  The most common form of authentication is the combination of a username
  and a password or passphrase. If both match values stored within a locally
  stored table, the user is authenticated for a connection. Password strength is
  a measure of the difficulty involved in guessing or breaking the password
  through cryptographic techniques or library-based automated testing of
  alternate values.

  A weak password might be very short or only use alphanumberic characters,
  making decryption simple. A weak password can also be one that is easily
  guessed by someone profiling the user, such as a birthday, nickname, address,
  name of a pet or relative, or a common word such as God, love, money or password.

  That is why CUPP was born, and it can be used in situations like legal
  penetration tests or forensic crime investigations.

Requirements
------------

You need Python 3 to run CUPP.

Quick start
-----------

    $ python3 cupp.py -h

## Options

  Usage: cupp.py [OPTIONS]

        -h      this menu

        -i      Interactive questions for user password profiling

        -w      Use this option to profile existing dictionary,
                or WyD.pl output to make some pwnsauce :)

        -l      Download huge wordlists from repository

        -a      Parse default usernames and passwords directly from Alecto DB.
                Project Alecto uses purified databases of Phenoelit and CIRT which where merged and enhanced.

        -v      Version of the program

## Configuration

   CUPP has configuration file cupp.cfg with instructions.

## Author

  Cann66
  https://github.com/cann66dev
