h5part = 0
NVCC = nvcc -g -I/opt/mpich/include/ -L/opt/mpich/lib/ -I/opt/hdf5_mpich/include/ -L/opt/hdf5_mpich/lib/ -I../
CXX = /opt/mpich/bin/mpicxx -g -L/opt/mpich/lib/ -L/opt/hdf5_mpich/lib/ -I../
NVCC_LINK_FLAGS=-L/usr/local/cuda-6.5/bin/..//lib64 \
	-L/usr/local/cuda-6.5/bin/..//lib64/stubs \
	-Wl,-rpath=/usr/local/cuda-6.5/bin/..//lib64
CXXFLAGS = ${NVCC_LINK_FLAGS} -I/usr/local/cuda-6.5/include/
