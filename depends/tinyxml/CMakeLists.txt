project(dfhack-tinyxml)
ADD_LIBRARY(dfhack-tinyxml STATIC EXCLUDE_FROM_ALL tinystr.cpp tinyxml.cpp tinyxmlerror.cpp tinyxmlparser.cpp)
IDE_FOLDER(dfhack-tinyxml "Depends")