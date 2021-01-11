# link video : https://youtu.be/8JvI8jaEKjI
1. Cập nhật phương pháp observe trong lớp ExactInference - inference.pyđể cập nhật chính xác sự phân bổ niềm tin của tác nhân đối với các vị trí ma được quan sát từ các cảm biến của Pacman
2.  Triển khai phương thức elapseTime trong ExactInference - có quyền truy cập vào phân phối hành động cho bất kỳ GhostAgent.
3. Thực hiện chooseActionphương pháp GreedyBustersAgenttrong bustersAgents.py - Trước tiên nhân viên của bạn nên tìm vị trí có khả năng xảy ra nhất của mỗi con ma còn lại (chưa bị bắt), sau đó chọn một hành động để giảm thiểu khoảng cách đến con ma gần nhất.

4.Thực hiện các chức năng initializeUniformly, getBeliefDistribution và observe cho các lớp ParticleFilter trong inference.py. Một triển khai đúng cũng cần xử lý hai trường hợp đặc biệt. (1) Khi tất cả các hạt của bạn nhận được trọng lượng bằng không dựa trên bằng chứng,  lấy mẫu lại tất cả các hạt từ trước khi thu hồi. (2) Khi một con ma bị ăn thịt, cập nhật tất cả các hạt để đặt con ma đó vào phòng giam của nó, như mô tả trong phần bình luận của observe.

5.Thực hiện chức năng elapseTime cho ParticleFilterlớp trong inference.py.

6.Hoàn thành initializeParticles, getBeliefDistribution và phương thức observeState trong JointParticleFilter và Resample the whole list của các hạt dựa trên bằng chứng mới. Như trước đây, một thực hiện đúng cũng cần xử lý hai trường hợp đặc biệt. (1) Khi tất cả các hạt  nhận được trọng lượng bằng không dựa trên bằng chứng,  lấy mẫu lại tất cả các điểm từ trước khi thu hồi. (2) Khi một con ma bị ăn thịt, cập nhật tất cả các điểm để đặt con ma đó vào phòng giam của nó.

7.Hoàn thành các elapseTime trong JointParticleFilter  trong inference.py để Resample từng điểm một cách chính xác cho mạng Bayes. Đặc biệt, mỗi con ma nên vẽ một vị trí mới với điều kiện vị trí của tất cả các con ma ở bước thời gian trước đó. Các chú thích trong phương pháp cung cấp hướng dẫn cho các chức năng hỗ trợ để giúp lấy mẫu và tạo phân phối chính xác.
