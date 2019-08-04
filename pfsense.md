#PFsense là gì ?
pfSense là một ứng dụng có chức năng định tuyến vào tường lửa mạnh và miễn phí, ứng dụng này sẽ cho phép bạn mở rộng mạng của mình mà không bị thỏa hiệp về sự bảo mật. Bẳt đầu vào năm 2004, khi m0n0wall mới bắt đầu chập chững– đây là một dự án bảo mật tập trung vào các hệ thống nhúng – pfSense đã có hơn 1 triệu download và được sử dụng để bảo vệ các mạng ở tất cả kích cỡ, từ các mạng gia đình đến các mạng lớn của của các công ty. Ứng dụng này có một cộng đồng phát triển rất tích cực và nhiều tính năng đang được bổ sung trong mỗi phát hành nhằm cải thiện hơn nữa tính bảo mật, sự ổn định và khả năng linh hoạt của nó.

Ngoài ra pfSense có đầy đủ các chức năng như một thiết bị cao cấp như: Stateful firewall, firewall rules, Traffic Shaper, NAT, DHCP Server and Relay Agent, Dynamic DNS, OpenVPN, IPSec VPN, Captiva Portal… và đi kèm thêm là một số chức năng mang tính sẵn sàng cao như Multi-WAN Loadbalancing, Failover CARP…

##Các tính năng nổi bật
PfSense là tường lửa mềm, tức là bạn chỉ cần một máy tính bất kì, hoặc tốt hơn là một máy chủ, rồi cài đặt pfSense là đã có     ngay một tường lửa mạnh mẽ cho hệ thống mạng trong doanh nghiệp. Trong phân khúc tường lửa cho doanh nghiệp vừa và nhỏ, với khoảng dưới 1000 người sử dụng, pfSense được đánh giá là tường lửa nguồn mở tốt nhất hiện nay với khả năng đáp ứng lên tới hàng triệu kết nối đồng thời. Không những thế, tường lửa pfSense còn có nhiều tính năng mở rộng tích hợp, tất cả trong một, vượt xa các tưởng lửa thông thường, kể cả các tường lửa cứng của các hãng nổi tiếng về thiết bị mạng.

 

- Tường lửa tầng L3, L4, L7
- Chặn truy cập theo khu vực địa lý
- Quản lý chất lượng QoS
- Proxy
- Quản trị mạng không dây
- Hỗ trợ VLAN
- Cân bẳng tải
- VPN theo 4 giao thức
- Giám sát/Phân tích mạng
- Quản lý tên miền (DC), hỗ trợ tên miền động (DynDNS)
- Cho phép chạy song hành, failover
- Hỗ trợ ngôn ngữ tiếng Việt (*)
- Tự động cập nhật black list.
- Tự động nâng cấp phiên bản

##Lợi ích mà pfSense đem tới
Hoàn toàn miễn phí, giá cả là ưu thế vượt trội của tường lửa pfSense. Tuy nhiên, rẻ không có nghĩa là kém chất lượng, tường lửa pfSense hoạt động cực kỳ ổn định với hiệu năng cao, đã tối ưu hóa mã nguồn và cả hệ điều hành. Cũng chính vì thê, pfSense không cần nền tảng phần cứng mạnh. Nếu doanh nghiệp không có đường truyền tốc độ cao, tường lửa pfSense chỉ cần cài đặt lên một máy tính cá nhân là có thể bắt đầu hoạt động. Điều đó càng góp phần làm giảm chi phí triển khai, đồng thời tạo nên sự linh hoạt, tính mở rộng/sẵn sàng chưa từng có, khi doanh nghiệp muốn có nhiều hơn một tường lửa.
Không chỉ là một tường lửa,  pfSense hoạt động như một thiết bị mạng tổng hợp với đầy đủ mọi tính năng toàn diện sẵn sàng bất cứ lúc nào. Khi có một vấn đề về hệ thống mạng phát sinh, thay vì phải loay hoay tìm thiết bị và mất thời gian đặt hàng, doanh nghiệp có thể kết hợp các tính năng đa dạng trên pfSense để tạo thành giải pháp hợp lý, khắc phục sự cố ngay lập tức.

Không kém phần quan trọng là khả năng quản lý. Tường lửa pfSense được quản trị một cách dễ dàng, trong sáng qua giao diện web. Hơn thế nữa, pfSense đã có giao diện web quản trị duy nhất bằng tiếng Việt, được các chuyên gia hệ thống mạng của Techlink biên dịch, nên việc sử dụng càng trở nên đơn giản và rõ ràng, giúp các nhà quản trị mạng thực sự thoải mái và thấu hiểu về mọi hoạt động của tường lửa.

Như vậy, tường lửa pfSense là sự kết hợp hoàn hảo và mạnh mẽ, đem lại sự hợp lý cho các nhà tài chính, và sự tin tưởng cho các nhà quản trị.

#Các tình huống ứng dụng
  
##Chặn truy cập vào trang web
###Sử dụng DNS
  Nếu DNS Forwarder hoặc DNS Resolver đang được sử dụng, có thể định cấu hình ghi đè sẽ phân giải tên miền của trang web để chặn địa chỉ IP không hợp lệ (chẳng hạn như 127.0.0.1).

###Sử dụng Firewall Rule

Thường một trang web hiếm khi thay đổi địa chỉ IP nên ta có thể chặn quyền truy cập vào nó bằng các quy tắc của tường lửa. Đây không phải là một giải pháp khả thi cho các trang web trả về mức độ thấp và phân tán tải trên nhiều máy chủ và hoặc trung tâm dữ liệu, như Google và các trang web rất lớn tương tự. Hầu hết các trang web cỡ nhỏ đến trung bình có thể bị chặn một cách hiệu quả bằng phương pháp này vì chúng hiếm khi thay đổi địa chỉ IP.

Tên máy chủ có thể được nhập vào bí danh mạng và sau đó bí danh đó có thể được áp dụng cho quy tắc chặn. Lưu ý mặc định tên máy chủ sẽ chỉ được giải quyết sau mỗi 5 phút, nhưng điều đó có thể được thay đổi trong System> Advanced trên tab Firewall / NAT 

Một tùy chọn khác là tìm tất cả các khối IP của trang web, tạo bí danh với các mạng đó và chặn lưu lượng truy cập đến các điểm đến đó. Điều này đặc biệt hữu ích với các trang web như Facebook trải rộng số lượng lớn không gian IP, nhưng bị hạn chế trong một vài khối mạng.

###Sử dụng Squidguard 
Các gói SquidGuard có thể được cấu hình để chặn các trang web.
Tham khao:
https://www.quantrimangdn.com/blogs/post/chan-website-bang-blacklist-tren-pfsense
Hoặc
https://github.com/hoangdh/ghichep-pfsense/blob/master/docs/Cau-hinh-chan-website-squidguard.md

###Ngăn chặn bypass 
Với bất kỳ phương pháp nào ở trên, vẫn còn nhiều cách để vượt qua các khối được xác định. Cách dễ nhất và có thể phổ biến nhất là sử dụng bất kỳ số lượng trang web proxy. Tìm và chặn tất cả các cá nhân này và giữ cho danh sách cập nhật là không thể. Cách tốt nhất để đảm bảo các trang web này không thể truy cập được là sử dụng tính năng lọc nội dung có khả năng chặn theo danh mục.

##IDS / IPS
pfSense® software can act in an Intrusion Detection System (IDS) / Intrusion Prevention System (IPS) role with add-on packages like Snort and Suricata.
Tham khảo cách cài đặt:
https://vorkbaard.nl/installing-snort-for-idsips-on-pfsense-2-4/


##DUAL-WAN LOAD BALANCING VÀ FAILOVER PFSENSE 
Server Load Balancing, or Inbound Load Balancing, provides redundancy for local hosted services using the relayd daemon. This is a simple service that does not have advanced capabilities and is only suited for small deployments with very basic requirements.



Tham khảo cách cài đặt:
https://www.cyberciti.biz/faq/howto-configure-dual-wan-load-balance-failover-pfsense-router/



Tổng quan về Pfsense:
https://docs.netgate.com/pfsense/en/latest/firewall/adding-rules-with-easyrule.html
