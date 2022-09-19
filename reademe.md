
cd build/

cmake -DGeant4_DIR=/home/gate/Geant4/v11_0_2/geant4-v11.0.2-install/lib/Geant4-11.0.2 ../

make -j 6

LD_LIBRARY_PATH=/home/gate/Geant4/v11_0_2/geant4-v11.0.2-install/lib/ ./exampleB2a run1.mac 


## additional info

## running QT
cmake -DCMAKE_INSTALL_PREFIX=/home/lorgum25/geant4.10.07.p02-install /home/lorgum25/geant4.10.07.p02 -DGEANT4_INSTALL_DATA=ON -DGEANT4_USE_OPENGL_X11=OFF -DGEANT4_USE_RAYTRACER_X11=ON -DGEANT4_USE_QT=ON -DGEANT4_USE_SYSTEM_EXPAT=ON -DCMAKE_PREFIX_PATH=/path/to/your/Qt5