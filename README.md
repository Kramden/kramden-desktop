To build source package:

  gbp buildpackage -S --git-ignore-branch


To upload to the PPA (replace VERSION):

  dput ppa:kramden-team/kramden  ../build-area/kramden-desktop_VERSION_source.changes

