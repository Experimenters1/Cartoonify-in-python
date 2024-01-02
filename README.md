# Cartoonify-in-python
## Cartoonify in python

## CartoonGAN: Generative Adversarial Networks for Photo Cartoonization paper with code <br><br>
## stable diffusion <br><br>
[**CartoonGAN.ipynb**](https://github.com/TobiasSunderdiek/cartoon-gan/blob/main/CartoonGAN.ipynb) <br><br>

[**CartoonGAN - my attempt to implement it**](https://tobiassunderdiek.github.io/cartoon-gan/#tc1_1) <br><br>

#

### Generate dataset (Tạo dữ liệu) <br><br>


#### Cartoon images

Trong bài báo gốc, dữ liệu được tạo ra bằng cách trích xuất hình ảnh từ các bộ phim anime, ví dụ như phim "Spirited Away" của Miyazaki Hayao. Do lý do bản quyền, tôi đã cố gắng tìm một bộ dữ liệu thay thế, và tôi đã tìm thấy trong bộ dữ liệu  [**safebooru**](https://www.kaggle.com/datasets/alamson/safebooru?resource=download)  từ kaggle. Vấn đề của quy trình này là sự khác biệt giữa các tác giả và phong cách hình ảnh khác nhau của họ. Điều này sẽ dẫn đến việc tạo ra dữ liệu huấn luyện mà từ đó khó có thể học hỏi được. Tôi nghĩ điều này sẽ không huấn luyện mạng lưới một cách đúng đắn, nhưng tôi vẫn sẽ thử. Trong bài báo, chỉ sử dụng một phong cách từ một họa sĩ duy nhất. <br><br>

Tôi thu thập phần dữ liệu hoạt hình cho việc triển khai mạng GAN hoạt hình của tôi theo cách sau: <br><br>
[**Code**](https://github.com/Experimenters1/Cartoonify-in-python/blob/main/Untitled1.ipynb) <br><br>

### 

### Edge-smoothed version of cartoon images (Phiên bản hình ảnh hoạt hình có viền mượt mà)


