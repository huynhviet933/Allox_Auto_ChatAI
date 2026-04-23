# Allox_Auto_ChatAI
1. CÀI ĐẶT THƯ VIỆN (Chạy lệnh này tại thư mục tool):
npm install fs-extra ethers axios https-proxy-agent chalk uuid luxon node-machine-id

2. CHUẨN BỊ CÁC FILE DỮ LIỆU:
- privatekey.txt: Dán danh sách Private Key ví (mỗi dòng 1 ví).
- proxy.txt: Danh sách Proxy (mỗi dòng 1 proxy, định dạng ip:port hoặc user:pass@ip:port).
- user_agents.txt: Danh sách User-Agent trình duyệt (mỗi dòng 1 cái).
- config.json: File cấu hình (copy đoạn dưới vào file):
{
  "max_threads": 5,
  "account_delay_min": 30,
  "account_delay_max": 60,
  "start_thread_delay_min": 5,
  "start_thread_delay_max": 10
}

3. CÁCH CHẠY TOOL:
- Lệnh chạy: node p2.js
- Lần đầu chạy tool sẽ yêu cầu nhập "License Key": Dán Key của bạn vào rồi Enter.
- Tool sẽ tự động chạy đa luồng, tự đổi Proxy khi lỗi và tự reset lượt chat vào 7h sáng mỗi ngày.

4. LƯU Ý:
- Mỗi Key bản quyền chỉ dính với 1 máy (HWID).
- Tool sẽ chat đến khi lượt còn lại của ví về mức 0-5 lượt để tối ưu Point.

Tham Gia NHóm tele : https://t.me/HVchannelss

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 1 Tháng 4u - 15u 6thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây

Donenat : https://huynhviet933.github.io/donate_viet_mmo/
