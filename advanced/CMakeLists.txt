include_directories(${CMAKE_CURRENT_SOURCE_DIR})

ADD_SUBDIRECTORY(Epetra_Basic_Perf)
ADD_SUBDIRECTORY(CurlLSFEM_example)
ADD_SUBDIRECTORY(DivLSFEM_example)
ADD_SUBDIRECTORY(Stratimikos_Solver_Driver)
ADD_SUBDIRECTORY(Stratimikos_Preconditioner)

INCLUDE(CPack)

