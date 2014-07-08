# NAME

Deeme::Backend::SQLite - SQLite Backend using DBI for Deeme

# SYNOPSIS

    use Deeme::Backend::SQLite;
    my $e = Deeme->new( backend => Deeme::Backend::SQLite->new(
          database => "/var/tmp/deeme.db",
          username     => "user",
          password      => "something",
          options         => { RaiseError=> 1 }
      ) );

# DESCRIPTION

Deeme::Backend::SQLite is a SQLite Backend using DBI for Deeme.

# AUTHOR

mudler <mudler@dark-lab.net>

# COPYRIGHT

Copyright 2014- mudler

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[Deeme](https://metacpan.org/pod/Deeme)
