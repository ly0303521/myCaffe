# myCaffe
模仿accuracy_layer.cpp，将错误样本序号打印出来。
tools/extra/ShowWrongPic.py 该文件是通过解析日志文件，打印出错误的样本
GLOG_logtostderr=0 GLOG_log_dir="/home/ly/caffe/Log" ./build/tools/caffe.bin test -model examples/images/lenet_train_test.prototxt -weights examples/mnist/lenet_iter_10000.caffemodel -iterations 100
运行测试模型的命令
