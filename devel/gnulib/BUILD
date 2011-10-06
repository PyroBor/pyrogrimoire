cd $SOURCE_DIRECTORY &&
#mkdir build/ &&
#for module in $GNULIB_MODULES ; do
#	module_tmpdir=$SOURCE_DIRECTORY/build/$module &&
#   ./gnulib-tool --create-testdir --dir=$SOURCE_DIRECTORY/build $module &&
./gnulib-tool --create-testdir --single-configure --conditional-dependencies \
     --no-vc-files  --dir=$SOURCE_DIRECTORY/build $GNULIB_MODULES &&

cd build &&
#   ./gnulib-tool --import  $GNULIB_MODULES &&
#	cd $module_tmpdir &&
#   ./configure &&
#   make
#done
default_build
