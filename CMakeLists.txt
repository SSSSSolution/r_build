cmake_minimum_required(VERSION 3.13)

project(
    r_build
    VERSION 1.0
)

#add_executable(null
#)

# install
install(FILES
    src/r_build
    DESTINATION bin/
    PERMISSIONS WORLD_EXECUTE OWNER_EXECUTE GROUP_EXECUTE
                OWNER_WRITE WORLD_READ OWNER_READ
)

