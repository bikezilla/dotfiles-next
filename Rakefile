require 'rake'

desc "Install homebrew apps"
task :homebrew do
  formulas = %w(
    ack
    autoconf
    cairo
    carthage
    cask
    cscope
    emacs
    erlang
    figlet
    fontconfig
    freetype
    fzf
    gdbm
    gettext
    ghostscript
    glib
    gmp
    gnutls
    htop
    hub
    icu4c
    ilmbase
    imagemagick
    jpeg
    libde265
    libevent
    libffi
    libheif
    libidn2
    libomp
    libpng
    libssh2
    libtasn1
    libtiff
    libtool
    libunistring
    libyaml
    little-cms2
    lua
    lzo
    macvim
    mercurial
    midnight-commander
    ncurses
    nettle
    node
    nspr
    nss
    openexr
    openjpeg
    openssl
    openssl@1.1
    p11-kit
    pcre
    perl
    pixman
    pkg-config
    poppler
    postgresql
    python
    python@2
    qt
    rabbitmq
    rbenv
    readline
    reattach-to-user-namespace
    redis
    ruby
    ruby-build
    s-lang
    scmpuff
    shared-mime-info
    sqlite
    swiftlint
    the_silver_searcher
    tmux
    tnef
    tree
    unbound
    vim
    watch
    webp
    wget
    wxmac
    x265
    xz
    yarn
    zsh
    zsh-lovers
  )

  exec "brew", "install", *formulas
end
