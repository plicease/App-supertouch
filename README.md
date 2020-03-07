# supertouch [![Build Status](https://secure.travis-ci.org/plicease/App-supertouch.png)](http://travis-ci.org/plicease/App-supertouch)

Touch with directories

# SYNOPSIS

```
% supertouch foo/bar/baz.txt
```

# DESCRIPTION

`supertouch` is a command similar to `touch`, except it creates the directories structure
necessary if it doesn't already exist.

# OPTIONS

- -v

    Turn on verbose mode.

# SEE ALSO

- touch

    Unix command touch.

- [File::Touch](https://metacpan.org/pod/File::Touch)

    Perl module for touching files.

- [Path::Tiny](https://metacpan.org/pod/Path::Tiny)

    Perl path handling module which also provides an interface for touching files.

# AUTHOR

Graham Ollis <plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2020 by Graham Ollis.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
