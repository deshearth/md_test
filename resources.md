* Papers
  * [Image Inpainting for Irregular Holes Using Partial Convolutions](https://arxiv.org/pdf/1804.07723.pdf)

https://medium.com/@buffaloal/build-caffe-with-anaconda-on-macos-1070a8d0a9fe

https://github.com/Yijunmaverick/GenerativeFaceCompletion


find caffe in face_seg_lib installation: https://github.com/davheld/GOTURN/issues/4

official doc for caffe installation: http://caffe.berkeleyvision.org/install_osx.html

for any .h file not found: find the file's location first (using sudo find / -name <filename>), then include the path into CPLUS_INCLUDE_PATH
last step: exec python script for face_seg, seg-fault appeared: https://github.com/yosinski/deep-visualization-toolbox/issues/100 (change the order of importing modules)

generate caffe.pb.h: https://github.com/BVLC/caffe/issues/1761


face_seg linker problem: add -lglog flag in the link.txt file in cmakefiles_dir
