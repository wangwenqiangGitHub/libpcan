remake_add_configurations(
  *.conf.remake
  INSTALL ${CMAKE_INSTALL_PREFIX}/src/${REMAKE_PROJECT_FILENAME}-${REMAKE_PROJECT_FILENAME_VERSION}
)
remake_add_configurations(
  blacklist-peak.conf
  INSTALL /etc/modprobe.d
)
