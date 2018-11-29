# DSDH-HashingCode
Source code của bài báo Deep Supervised Discrete Hashing (https://papers.nips.cc/paper/6842-deep-supervised-discrete-hashing.pdf)
Qi Li, Zhenan Sun, Ran He and Tieniu Tan.
Source code chạy thử dựa trên tập dữ liệu CIFAR-10 với sự hỗ trợ của DSDH thuật toán. Thông tin chi tiết vui lòng liên hệ (https://cs.nju.edu.cn/lwj/).

Giai đoạn 1
1. Tải tập dữ liệu CIFAR-10 từ  
   website(https://www.cs.toronto.edu/~kriz/cifar-10-matlab.tar.gz), giải nén ra tệp tin 'cifar-10-batches-mat/',chuyển tệp tin này vào tập tin trên (DSDH folder).
   
2. Tải bộ Pretrained CNN model VGG-F 
   từ website(http://www.vlfeat.org/matconvnet/models/imagenet-vgg-f.mat), 
   và chuyền nó vào tệp tin trên.
   
Giai đoạn 2:                                                                             
1. Cài đặt và khởi động thư viện MatConvNet, các bước để có thể cài đặt và khởi động MatConvNet :
   - Khởi tạo môi trường
      - Tải Visual Studio 2015 (Professional/Communnity) bắt buộc phải sử dụng bản 2015 do các bản khác không truy xuất file bin rõ ràng
      - Tải Matlab 2015a trở lên ( Khuyến khích 2017a/b)
      - Tải Cuda 8.061 (Bắt buộc / Phiên bản ổn đinh nhất )
      - Tải Cudnn 5.1 (Bắt buộc)
      - Tải MatConvNet-1.0-beta24 tại trang web http://www.vlfeat.org/matconvnet/download/
      - Xem video sau để biết rõ về các bước chạy của MatConvNet https://www.youtube.com/watch?v=DWNyp1xZ-ks
   - Cài đặt
      -  Chạy visual studio, matlab, Cuda. Sau đó copy file cudnn vào file Cuda với đường dẫn C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0.
      - Sau khi hoàn thành các bước trên, tiến hafnnh giải nén MatConvNet và thực hiện các bước theo trang sau để khởi động thư viện http://www.vlfeat.org/matconvnet/install/
  
2.Sau khi cài đặt hoàn tất MatConvNet, chạy main.m trên matlab để kiểm thử.
