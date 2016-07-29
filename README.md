# Process_Data_Before_ML
Chương trình này sẽ đưa ảnh grayscale về dạng feature.

Bước 1 : Chương trình sẽ lấy tất cả các tên file ảnh có trong thư mục bằng function <b>getFileNames(tên_thư_mục)</b> trong class GetFileName
Bước 2 : Chương trình sẽ ghi tên file lấy được ra bằng function <b>writeNameToFile(tên_file)</b> trong class GetFileName.
Bước 3 : Chương trình truy cập vào file chưa tên của các ảnh vừa lưu ở bước 2 sau đó dùng thư viện <b><i>OpenCV</i></b> để xử lý đưa về feature
: function <b>convertData(file_chứa_tên, file_cần_lưu_đến, tên_nhãn)</b>

Ngoài ra chương trình còn có chức năng lưu features của tập test đó là overload của <b>convertData</b> với 2 biến tên_file_nguồn, tên_file_đích.

Và chức năng thứ 3 là nối kết quả từ file chứa kết quả tập test với các ảnh ứng với kết quả đó bằng function 
<b>concatFileInFolder(tên_folder_chưa_tập_test, tên_file_chứa_kết_quả)</b>.
