# Các giải pháp kỹ thuật được áp dụng

- Palo Alto Network – Nextgen Firewalls : https://docs.paloaltonetworks.com/pan-os/9-1/pan-os-web-interface-help/web-interface-basics/features-and-benefits
- McAfee – Nextgen IPS:
    - https://websecurityworks.com/Network-Security-Platform-M-1250.asp
    - https://www.websecurityworks.com/datasheets/ds-network-security-platform-m-series_new.pdf 
- CyberArk PAM : https://docs.cyberark.com/PAS/11.4/en/Content/PASIMP/OPM-PAM-LP.htm
- Crowdstrike : 
    - https://www.crowdstrike.com/products/endpoint-security/falcon-prevent-antivirus/ 
    - https://www.crowdstrike.com/products/endpoint-security/falcon-insight-xdr/ 
    - https://www.crowdstrike.com/products/endpoint-security/falcon-firewall-management/ 
    - https://www.crowdstrike.com/products/endpoint-security/falcon-device-control/ 
    - https://www.crowdstrike.com/products/threat-intelligence/falcon-sandbox-malware-analysis/ 

- TENABLE: https://www.tenable.com/ 
- AWS WAF: https://aws.amazon.com/vi/waf/features/
- IBM : 
    - SIEM : https://www.ibm.com/products/qradar-siem
    - SOAR : https://www.ibm.com/products/qradar-soar 
- Office 365 Security: 
    - https://learn.microsoft.com/en-us/microsoft-365/security/office-365-security/?view=o365-worldwide
    - https://www.microsoft.com/vi-vn/security/business/siem-and-xdr/microsoft-defender-office-365
- SAN : 
    > SAN, viết tắt của Storage Area Network, là mạng chuyên dụng để kết nối các Server và thiết bị lưu trữ nhằm mục đích truyền tải dữ liệu giữa các phần tử lưu trữ với nhau và giữa hệ thống máy tính và phần tử lưu trữ. 
    > Mạng SAN tách biệt hoàn toàn với các mạng LAN và WAN. SAN có khả năng kết nối tất cả các tài nguyên lưu trữ trong mạng với nhau. Vì SAN là mạng tốc độ cao dành riêng cho việc lưu trữ và quản trị dữ liệu, do đó người dùng có thể sử dụng và quản trị tài nguyên lưu trữ hiệu quả hơn, giúp quản lý tập trung các thao tác nhằm tăng độ an toàn, đồng thời sao lưu và khôi phục khi xảy ra sự cố. 

    >Tại sao nên sử dụng SAN? 
    >- Khắc phục vấn đề suy giảm băng thông mạng LAN 
    >- Tăng cường bảo mật dữ liệu
    >- Sao lưu khôi phục dễ dàng 
    >- Tăng khả năng mở rộng
- ORACLE DATABASE FIREWALL:
    > ORACLE DATABASE FIREWALL tạo ra một vành đai phòng thủ bên trong để giám sát và thực thi hành vi ứng dụng thông thường, giúp ngăn chặn việc tiêm SQL, bỏ qua ứng dụng và các hoạt động độc hại khác tiếp cận cơ sở dữ liệu 
    > Các tính năng: 
    > - Các mô hình triển khai linh hoạt bao gồm giám sát và chặn 
    > - Chính sách dựa trên back list, white list và exception list 
    > - Kiến trúc có khả năng mở rộng cao cho các ứng dụng doanh nghiệp 
    > - AD Authentication - Permission 
    > - Auditing Sensitive Data 
    > - Data Theft Protection 
    > - Database Vulnerability 
    > - Audit Access to Cardholder Information 
    > - Dynamic Data Masking 
    > - Hàng chục báo cáo tuân thủ có thể tùy chỉnh được tích hợp sẵn 
    > - Cảnh báo bảo mật theo thời gian thực 
    > - Hỗ trợ Oracle, MySQL, Microsoft SQL Server, Sybase và IBM DB2 
    > - Hỗ trợ TDE bảo mật nâng cao của Oracle (Transparent Data Encryption) 
- MPLS:
    > MPLS (Multiprotocol Label Switching) là một loại công nghệ chuyển tiếp dữ liệu có khả năng thông qua các đường dẫn mạng được định sẵn trong kỹ thuật MPLS để gia tăng tốc độ kết nối mạng internet và kiểm soát luồng lưu lượng mạng. Thay vì yêu cầu tra cứu phức tạp hơn trong bảng định tuyến tại những nơi mà các dữ liệu dừng lại thì chúng sẽ được truyền dẫn qua các label với MPLS. 

    >Hiểu đơn giản, mạng internet sẽ thực hiện việc chuyển ngẫu nhiên các packet từ router này sang router khác và đến packet cuối cùng để các dữ liệu mạng có thể hoạt động được. Điều này sẽ gây tốn rất nhiều thời gian khi người dùng thực hiện truy xuất.  
    >Với MPLS, công nghệ này đã xác định được trước đường truyền và packet đích để chuyển dẫn theo đường dẫn. Do đó, các router tiết kiệm được nhiều thời gian hơn trong việc đưa ra quyết định nơi mà các gói tin chuyển phát đến và đảm bảo các gói tin này sẽ luôn đi theo một đường dẫn. Như vậy, tốc độ mạng sẽ được tăng tốc đáng kể. 
- VMware vSphere:
    >Vmware vSphere sở hữu những chức năng tương tự như với hai loại VMware Work Station và VMware Server, nhưng VMware vSphere có khả năng sử dụng được trên phạm vi rộng hơn để phù hợp với các doanh nghiệp, các tổ chức lớn. Mục đích chính của VMware được sử dụng là để tạo ra cơ sở hạ tầng. Nó bao gồm một bộ các ứng dụng ảo hóa dành cho doanh nghiệp, trong đó nền tảng là ESX/ESXi. 

    >VMware vCenter Server cung cấp một điểm kiểm soát duy nhất cho cả trung tâm dữ liệu. vCenter thực hiện chức năng của một dịch vụ trung tâm dữ liệu cần thiết ví dụ như: kiểm soát truy cập, cấu hình, giám sát hiệu suất 

    >Phần mềm VMware vSphere cho chúng ta nhiều lợi ích như : 
    >- Di chuyển nhanh chóng các máy ảo sang một hệ thống khác mà không có downtime. 
    >- Di chuyển động các máy ảo sang các phân vùng storage khác mà không có downtime. 
    >- Hỗ trợ mở rộng tài nguyên CPU, RAM của host, không cần có downtime. 
    >- Bảo mật dữ liệu, thực hiện backup và restore các máy ảo. 
    >- Đảm bảo tính liên tục của ứng dụng ngay cả trong tình huống server bị lỗi mà dữ liệu không bị mất. 
    >- Cho phép các bên thứ 3 sử dụng các APIs này cho các ứng dụng backup. 
    >- Quản lý tập trung tài nguyên các server thành 1 khối và tự động cân bằng tải. 
    >- Đảm bảo tính liên tục của công việc khi một hệ thống có lỗi. 
    >- Cho phép tạo, cấu hình và duy trì các vùng bảo mật riêng biệt. 
    >- Quản lý tập trung và theo dõi các kết nối mạng sử dụng cluster-level. 
    >- Quản lý, theo dõi và tự động cân bằng tải trên các thiết bị storage và network. 
    >- Tạo các máy ảo thông qua các template. 
    >- Tự động triển khai các host với ESXi. 
    >- Lựa chọn storage theo các policy đã định nghĩa sẵn.
    >- Tự động cân bằng tải trên storage. 
    >- Kết hợp các traffic từ nhiều cổng song song vào 1 giao diện quản lý. 
- Route53:
    > Amazon Route 53 là một dịch vụ DNS có khả năng duy trì mở rộng cao. 

- On premise:
    >On premise hay được biết đến là những phần cứng hay phần mềm tại chỗ. Đây là một giải pháp công nghệ hỗ trợ lưu trữ dữ liệu tại chỗ. Phần mềm On premise yêu cầu doanh nghiệp mua giấy phép hoặc bản sao của phần mềm để sử dụng được phần mềm đó.


    | Yếu tố     | On-premise                                                             | Cloud                                                           |
    | ---------- | ---------------------------------------------------------------------- | --------------------------------------------------------------- |
    | Triển khai | Tài nguyên được triển khai nội bộ trên cơ sở hạ tầng của doanh nghiệp. | Tài nguyên được triển khai trên cloud.                          |
    | Chi phí    | Doanh nghiệp chị chi phí cao hơn                                       | Doanh nghiệp chỉ phải trả phí cho mức tài nguyên mà họ sử dụng. |
    | Kiểm soát  | Hoàn toàn kiểm soát được các hoạt động liên quan đến dữ liệu           | Không hoàn toàn kiểm soát được vì lưu trữ dữ liệu ở bên thứ 3   |
    | Bảo mật    | Mang mức độ bảo mật, quyền riêng tư cao hơn                            | Cần phải chọn dịch vụ uy tín                                    |


- AWS Direct Connect :
    > AWS Direct Connect là dịch vụ mạng cung cấp lựa chọn thay thế cho việc kết nối với AWS qua Internet. Khi bạn sử dụng AWS Direct Connect, những dữ liệu trước đây được truyền qua Internet giờ sẽ được cung cấp qua một kết nối mạng riêng giữa cơ sở của bạn và AWS 

