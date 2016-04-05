SN_ADD_EXECUTABLE( Picking PickingMain.cpp )
SN_LINK_LIBRARIES( Picking osgSim osgViewer osgText osgGA osgDB osgUtil osg OpenThreads )
SN_ADD_EXECUTABLE( RectangularPicking RectangularPickingMain.cpp )
SN_LINK_LIBRARIES( RectangularPicking osgSim osgViewer osgText osgGA osgDB osgUtil osg OpenThreads )
