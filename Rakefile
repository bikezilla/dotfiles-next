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
    hivemind
    htop
    hub
    icu4c
    ilmbase
    imagemagick
    jpeg
    kubernetes-cli
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

desc 'Install Homebrew Casks'
task :casks do
  formulas = %w(
    1password
    bartender
    caffeine
    chromedriver
    commander-one
    dash
    firefox
    fluor
    garmin-basecamp
    google-chrome
    google-earth-pro
    google-hangouts
    iterm2
    kindle
    octomouse
    phantomjs
    qbserve
    slack
    spectacle
    spotify
    tunnelblick
    viber
    visual-studio-code
    wkhtmltopdf
    zoomus
  )

  exec "brew", "cask", "install", *formulas
end
