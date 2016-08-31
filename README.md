# NAME

WWW::Baidu::ZhanZhang - Baidu ZhanZhang push links

# SYNOPSIS

    use WWW::Baidu::ZhanZhang;

    my $zz = WWW::Baidu::ZhanZhang->new(
      site  => 'betsapi.com',
      token => 'abc'
    );

    my $data = $zz->post_urls('http://betsapi.com/c/Soccer', 'http://betsapi.com/c/Tennis');

# DESCRIPTION

you can get the token from [http://zhanzhang.baidu.com/linksubmit/index](http://zhanzhang.baidu.com/linksubmit/index)

# AUTHOR

Fayland Lam <fayland@gmail.com>

# COPYRIGHT

Copyright 2016- Fayland Lam

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO
