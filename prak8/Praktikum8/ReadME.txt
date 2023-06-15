untuk pengguna visual studio
apabila terjadi eror ubah semua #include <GL/glut.h> menjadi #include <glut.h>

untuk pengguna devC++
apabila terjadi eror tambahkan di project - project options - parameters 
-lopengl32
-lfreeglut
-lglu32
-lwinmm