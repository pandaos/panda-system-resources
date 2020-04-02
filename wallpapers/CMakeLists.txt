project(wallpapers)

FILE (GLOB ALL_SOURCES "*.jpg")

install(FILES ${ALL_SOURCES} DESTINATION /usr/share/wallpapers/panda/)
