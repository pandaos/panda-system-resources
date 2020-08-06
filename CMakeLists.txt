cmake_minimum_required(VERSION 3.5)
project(panda-themes)

include(FeatureSummary)

install(DIRECTORY Lucia DESTINATION /usr/share/icons)
install(DIRECTORY Lucia-dark DESTINATION /usr/share/icons)
add_subdirectory(Wallpapers)
