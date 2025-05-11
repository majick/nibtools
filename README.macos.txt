To build on macOS:

% brew install opencbm cc65
% make -f GNU/Makefile -j unix CBM_LNX_PATH=$(brew --prefix opencbm)

# To install to your home directory:
% make -f GNU/Makefile install

# To install somewhere else:
% make -f GNU/Makefile install INSTALL_PREFIX=/usr/local
