art_make(LIB_LIBRARIES
           larsim_MCCheater_BackTrackerService_service
           larsim_MCCheater_ParticleInventoryService_service
           nug4_ParticleNavigation
           nusimdata_SimulationBase
           lardata_RecoObjects
           larcorealg_Geometry
           larreco_Calorimetry
           art_Utilities
           ${ART_FRAMEWORK_PRINCIPAL}
           ${ART_PERSISTENCY_PROVENANCE}
           ${ART_ROOT_IO_TFILESERVICE_SERVICE}
           ${ART_ROOT_IO_TFILE_SUPPORT}
           ${ART_FRAMEWORK_SERVICES_REGISTRY}
           canvas
           cetlib
           cetlib_except
           ${ROOT_CORE}
           ${ROOT_GENVECTOR}
           ${ROOT_GPAD}
           ${ROOT_GRAF}
           ${ROOT_GRAF3D}
           ${ROOT_HIST}
           ${ROOT_MATHCORE}
           ${ROOT_MATRIX}
           ${ROOT_RIO}
           ${ROOT_TREE}
           ${ROOT_TMVA}
        )

add_subdirectory(TCDebugTools)

install_headers()
install_source()
