# mpi_cpp
openMPI c++

|MPI data Type	| C data Type |
|:--------------|:---------------|
|MPI_BYTE       |	8 binary digits|
|MPI_CHAR       |	char |
|MPI_UNSIGNED_CHAR|	unsigned char|
|MPI_SHORT|	signed short int|
|MPI_UNSIGNED_SHORT|	unsigned short int|
|MPI_INT|	signed int|
|MPI_UNSIGNED|	unsigned int|
|MPI_LONG	signed| long int|
|MPI_UNSIGNED_LONG|	unsigned long int|
|MPI_FLOAT|	float|
|MPI_DOUBLE|	double|
|etc.||
|MPI_PACKED|	define your own with|


|Operation	| Description	| Datatype
|:---|:----|:---|
|MPI_MAX|	maximum|	integer,float|
|MPI_MIN|	minimum|	integer,float|
|MPI_SUM|	sum|	integer,float|
|MPI_PROD|	product|	integer,float|
|MPI_LAND|	logical AND|	integer|
|MPI_BAND|	bit-wise AND|	integer,MPI_BYTE|
|MPI_LOR|	logical OR|	integer|
|MPI_BOR|	bit-wise OR|	integer,MPI_BYTE|
|MPI_LXOR|	logical XOR	|integer|
|MPI_BXOR|	bit-wise XOR| integer,MPI_BYTE|
|MPI_MAXLOC|	max value and location|	float|
|MPI_MINLOC|	min value and location|	float|

