# Session 06-DApps,Web3&Ecosystem

- Student: Lê Thị Bích Ngọc
-Github:https://github.com/lngoccccccc07000/Sessions-06-DApps-Web3-Ecosystem
- Submitted: 2026-11-24
- Commit:https://github.com/lngoccccccc07000
## 1. Summary
-Smart contract thực thi quy tắc trên blockchain; token là tài sản do hợp đồng quản lý; stablecoin, NFT và phí gas là các dạng ứng dụng hoặc cơ chế khác nhau của token.
## 2. Topic notes
1. Smart contract
-Địa chỉ giúp nhận diện một tài khoản hoặc hợp đồng trên một mạng.

-Ví giúp quản lý quyền ký và tạo giao dịch. 

-Trạng thái là dữ liệu hiện tại, chẳng hạn số dư token hoặc danh sách địa chỉ đã đăng ký.

-Ví dụ register(): kiểm tra địa chỉ chưa đăng ký → thêm vào danh sách → tăng bộ đếm.

-Hạn chế: hợp đồng chỉ nhận diện địa chỉ; một người có thể có nhiều địa chỉ.

-"Lịch sử khó sửa” ≠ “trạng thái không đổi”: chuyển vé đổi chủ sở hữu nhưng vẫn lưu lịch sử.

3. Coin và token

-Phân biệt
<img width="802" height="229" alt="image" src="https://github.com/user-attachments/assets/fa62fbea-255a-4b73-bd7c-c6a04b6c6cf5" />

-Mint tạo thêm đơn vị token. Burn hủy đơn vị token theo cơ chế của hợp đồng và làm giảm tổng cung tương ứng. Transfer chuyển token giữa các địa chỉ; với token thông thường, thao tác này không làm tăng tổng cung.

-Không phải ai cũng được mint hoặc burn. Quyền này phụ thuộc vào mã và vai trò được cấp. Token có thể có giới hạn tổng cung, quyền mint chỉ dành cho một địa chỉ hoặc cơ chế mint theo điều kiện.

-Lưu ý: token cùng tên trên hai mạng không tự động tương thích; gửi tới địa chỉ không dùng được chưa chắc là burn
<img width="801" height="178" alt="image" src="https://github.com/user-attachments/assets/50807a64-babf-4c31-a16d-a925af79c077" />

5. Stablecoin
  -Stablecoin cố gắng bám theo một giá tham chiếu, thường là 1 USD.
   
 - 3 cơ chế:Dựa vào dự trữ;Thế chấp bằng tài sản mã hóa;Dựa nhiều vào thuật toán hoặc động lực thị trường.
 - 
 - Ví dụ depeg: 1 token chỉ đổi 0,97 USD → 100 token ≈ 97 USD.
 - 
 - Phân biệt: chuyển token trên blockchain thành công ≠ chắc chắn đổi được ra tiền thật.

4. NFT
-Với NFT, mỗi token được nhận diện riêng.

-Ba thành phần: token, metadata, quyền sử dụng — có thể nằm ở nơi khác nhau.

-Ví dụ vé 128: token ID không đổi sau chuyển,tổng cung không đổi.

-Metadata/ảnh có thể lưu ngoài chuỗi và có thể mất khả năng hiển thị.

-Sở hữu NFT không tự động là sở hữu bản quyền hình ảnh.

-Cách đọc trang NFT: mạng → contract address → token ID → owner → metadata → điều khoản quyền sử dụng.

6. Phí giao dịch và nơi chạy hợp đồng
-Gas đo lượng công việc tính toán của giao dịch trên Ethereum.

-Transaction fee là số tiền trả cho lượng gas đã dùng. 

-Giao dịch thất bại nhưng i vẫn có thể tốn phí.

-Phân biệt
<img width="801" height="261" alt="image" src="https://github.com/user-attachments/assets/2c8af0e4-284a-4d18-9f89-fce7a7a669af" />
8. Đọc token trên Etherscan
## 3. Work completed
Không có
## 4. Evidence
Không có
## 5. Blockers
Khoing có
## 6. Takeaway
Không có

