# Copyright (C) 2011 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( lua-bit-numberlua NONE)
cmake_minimum_required ( VERSION 2.6 )
include ( dist.cmake )

INSTALL(DIRECTORY module/lmod/bit DESTINATION ${INSTALL_LMOD})
INSTALL(FILES COPYRIGHT DESTINATION ${INSTALL_DATA})
