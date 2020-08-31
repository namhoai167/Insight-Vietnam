# Percentage of vaccination and Child mortality rate in Vietnam
Dữ liệu lấy từ [Tổng cục thống kê](https://www.gso.gov.vn)

2.18 Tỷ suất chết của trẻ em dưới 1 tuổi phân theo địa phương  
- Tỷ suất chết của trẻ em dưới một tuổi (Trẻ em dưới năm tuổi tử vong/1000 trẻ sinh sống)
- Từ năm 2008 tới nay, số liệu thành phố Hà Nội bao gồm cả tỉnh Hà Tây.

2.19 Tỷ suất chết của trẻ em dưới 5 tuổi phân theo địa phương  
- Tỷ suất chết của trẻ em dưới năm tuổi (Trẻ em dưới năm tuổi tử vong/1000 trẻ sinh sống)

11.02 Số cơ sở khám, chữa bệnh  
- Chưa kể cơ sở tư nhân.

11.05 Số cơ sở khám, chữa bệnh trực thuộc sở Y tế phân theo địa phương  
- Chưa kể cơ sở tư nhân.
- Từ năm 2008 tới nay, số liệu thành phố Hà Nội bao gồm cả tỉnh Hà Tây. 

11.07 Số giường bệnh  
- Số liệu từ năm 2015-2018 không bao gồm số giường bệnh thuộc cơ sở tư nhân.
- Số liệu năm 2019 không bao gồm số giường bệnh thuộc tuyến Trung ương quản lý.
- Giường bệnh tính bình quân cho 1 vạn dân không bao gồm số giường của trạm y tế xã, phường, cơ quan, xí nghiệp.

11.10 Số giường bệnh trực thuộc sở Y tế phân theo địa phương  
- Chưa kể cơ sở tư nhân.
- Giai đoạn 2002 - 2003, số liệu của tỉnh Lai Châu bao gồm cả tỉnh Điện Biên, tỉnh Đắk Lắk bao gồm cả tỉnh Đắk Nông, 
thành phố Cần Thơ gồm cả tỉnh Hậu Giang.
- Từ năm 2008 tới nay, số liệu thành phố Hà Nội bao gồm cả tỉnh Hà Tây.

11.11 Số nhân lực y tế  
- Chưa kể cơ sở tư nhân.
- Số liệu Cán bộ ngành y - Bác sĩ năm 2019 không bao gồm số bác sĩ thuộc tuyến Trung ương quản lý.
- Cán bộ ngành dược năm 2012 bao gồm cả nhân lực ngành dược của các cơ sở y tế tư nhân.

11.16 Tỷ lệ trẻ em dưới một tuổi được tiêm chủng đầy đủ các loại vắc xin phân theo địa phương
- Đơn vị tính theo phần trăm (%)

Dữ liệu được chọn để tiền xử lý là 11.16 Tỷ lệ trẻ em dưới một tuổi được tiêm chủng đầy đủ các loại vắc xin phân theo địa phương, 2.18 Tỷ suất chết của trẻ em dưới 1 tuổi phân theo địa phương và 2.19 Tỷ suất chết của trẻ em dưới 5 tuổi phân theo địa phương.
Dữ liệu sau khi tiền xử lý và join 3 file trên là "Tỷ lệ tiêm chủng và tỷ suất chết của trẻ em Việt Nam.csv". Dữ liệu gồm 5 trường:
- Khu vực: Gồm 71 giá trị là Cả nước, 6 vùng kinh tế (gồm Trung du và miền núi phía Bắc, Đồng bằng sông Hồng, Bắc Trung Bộ và Duyên hải miền Trung, Tây Nguyên, Đông Nam Bộ và Đồng bằng sông Cửu Long) và 63 tỉnh thành phố
- Năm: gồm 8 giá trị là từ 2013 đến 2019
- Tỷ lệ trẻ em dưới một tuổi được tiêm chủng đầy đủ các loại vắc xin
- Tỷ suất chết của trẻ em dưới 1 tuổi
- Tỷ suất chết của trẻ em dưới 5 tuổi
