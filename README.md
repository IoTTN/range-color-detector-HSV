# range-color-detector-HSV
range color detector HSV python
ìm màu sắc trong HSVkhông gian là một câu hỏi cũ nhưng phổ biến. Tôi đã hsv-colormaptìm kiếm nhanh màu đặc biệt. Nó đây:

nhập mô tả hình ảnh ở đây

Trục x biểu thị Huetrong [0,180), trục y1 biểu thị Saturationtrong [0,255], trục y2 biểu thị S = 255, trong khi giữ nguyên V = 255.

Để tìm một màu, thường chỉ cần tìm kiếm phạm vi Hvà Svà đặt v trong phạm vi (20, 255).

Để tìm màu cam, chúng ta nhìn lên cho bản đồ, và tìm ra phạm vi tốt nhất: H :[10, 25], S: [100, 255], and V: [20, 255]. Vì vậy, mặt nạ làcv2.inRange(hsv,(10, 100, 20), (25, 255, 255) )
