
if(BUILD_GUI)
    add_subdirectory(Gui)
endif(BUILD_GUI)


INSTALL(
    FILES
        Init.py
        InitGui.py
        CEM.py
        CEMGui.py
        lattice.py
    DESTINATION
        Mod/Cem
)

