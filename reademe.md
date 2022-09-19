
cd build/

cmake -DGeant4_DIR=/home/gate/Geant4/v11_0_2/geant4-v11.0.2-install/lib/Geant4-11.0.2 ../

make -j 6

LD_LIBRARY_PATH=/home/gate/Geant4/v11_0_2/geant4-v11.0.2-install/lib/ ./exampleB2a run1.mac 
