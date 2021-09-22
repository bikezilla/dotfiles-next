require 'rake'

desc "Install homebrew apps"
task :homebrew do
  system 'brew unlink macvim' # need to unlink default

  formulas = %w(
    ack
    anycable-go
    fzf
    heroku
    hivemind
    htop
    hub
    macvim
    minicom
    mosquitto
    node
    picocom
    postgresql
    python
    qt
    rabbitmq
    rbenv
    reattach-to-user-namespace
    redis
    scmpuff
    the_silver_searcher
    tmux
    vim
    macvim
    wget
    yarn
    zsh
  )

  exec "brew", "install", *formulas
end

desc 'Install Homebrew Casks'
task :casks do
  formulas = %w(
    1password
    brave-browser
    dash
    firefox
    gimp
    google-chrome
    google-drive
    google-earth-pro
    iterm2
    kindle
    marta
    rar
    raspberry-pi-imager
    silicon-labs-vcp-driver
    slack
    spectacle
    spotify
    tunnelblick
    viber
    visual-studio-code
    vlc
    wkhtmltopdf
    zoomus
  )

  exec "brew", "cask", "install", *formulas
end
