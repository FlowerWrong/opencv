task default: %w[clean]

desc "clean ignore file"
task :clean do
  sh "rm -rf Makefile CMakeCache.txt cmake_install.cmake CTestTestfile.cmake CMakeFiles cmake-build-debug"
  sh "rm -rf *.a *.dylib *.so *.cbp *.log vgcore.*"
  sh "rm -rf cv"
end
