# QtViewer

This project only supports windows platform x64.

Basic implementation for viewing polyhedral mesh based on Qt GUI.

Now this code includes a basic implementation for OpenGL rendering and arcball for user interaction.

Dependencies: CGAL and Qt5.

Install CGAL and Qt for Windows. 

##Make sure the following environment variables are set: <br />
BOOST_LIBRARYDIR = ${BOOST_LOCAL_DIR}\lib64-msvc-xx.0 <br />
BOOST_INCLUDEDIR = ${BOOST_LOCAL_DIR} <br />
CGAL_DIR = ${CGAL_LOCAL_DIR} <br />
Qt5_DIR = ${Qt5_LOCAL_DIR}\5.xx.0\msvcxxxx_64

##Add the following environment variables to PATH: <br />
${BOOST_LOCAL_DIR}lib64-msvc-14.0 <br />
${CGAL_LOCAL_DIR}\auxiliary\gmp\lib <br />
${CGAL_LOCAL_DIR}\build\bin <br />
${Qt5_LOCAL_DIR}\5.xx.0\msvcxxxx_64\bin <br />
${Qt5_LOCAL_DIR}\5.xx.0\msvcxxxx_64\plugins\platforms

##Copy the following files to .exe folder from ${Qt5_LOCAL_DIR}\5.xx.0\msvcxxxx_64\bin: <br />
libEGL.dll <br />
libGLESv2.dll <br />
Qt5Core.dll <br />
Qt5Gui.dll <br />
Qt5OpenGL.dll <br />
Qt5Widgets.dll

##Copy the following folder to .exe folder: <br />
${Qt5_LOCAL_DIR}\5.xx.0\msvcxxxx_64\plugins\platforms
