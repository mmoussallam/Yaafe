install(FILES ${CMAKE_CURRENT_SOURCE_DIR}/yaafe DESTINATION ${CMAKE_INSTALL_BINDIR} PERMISSIONS OWNER_EXECUTE OWNER_WRITE OWNER_READ GROUP_EXECUTE GROUP_READ)
install(FILES yaafefeatures.py DESTINATION ${CMAKE_INSTALL_YAAFE_EXTENSIONS})
install(DIRECTORY yaafelib DESTINATION ${CMAKE_INSTALL_PYTHON_PACKAGES} FILES_MATCHING PATTERN "*.py" PATTERN ".svn" EXCLUDE)

