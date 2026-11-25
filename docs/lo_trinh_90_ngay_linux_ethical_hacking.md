# KẾ HOẠCH 90 NGÀY — LINUX & ETHICAL HACKING

> Mục tiêu: xây nền Linux, Networking, scripting và Web Security để tiến tới Penetration Tester / Linux Security Engineer.

## Cách sử dụng
- Mỗi ngày 60–90 phút: 15 phút học khái niệm, 45–60 phút thực hành, 10–15 phút ghi chép.
- Đánh dấu `[x]` sau khi hoàn thành **và giải thích được** kết quả; không chỉ chạy lệnh.
- Lưu bằng chứng ở `notes/day-XX.md`; tuyệt đối không commit mật khẩu, token, IP nhạy cảm hoặc dữ liệu thật.
- Chỉ kiểm thử máy, ứng dụng, lab thuộc quyền sở hữu hoặc đã được cho phép bằng văn bản. Không scan mục tiêu công khai tùy tiện.
- Lab khuyên dùng: Ubuntu WSL2 để học lệnh, Ubuntu Server VM riêng cho network/security; Kali chỉ bổ sung khi cần.

## Thước đo tiến độ
- [ ] 30/30 ngày đầu: thao tác Linux cơ bản tự tin
- [ ] 60/60 ngày: hiểu network, viết script xử lý log
- [ ] 90/90 ngày: hoàn thành một security assessment trên lab và báo cáo

## Checklist từng ngày

### Tuần 01 — Linux CLI & filesystem

- [ ] **Ngày 01 — Terminal, shell, pwd, ls, cd**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-01.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 02 — Filesystem hierarchy: /etc, /var, /home, /proc**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-02.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 03 — mkdir, touch, cp, mv, rm an toàn**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-03.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 04 — cat, less, head, tail, wc**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-04.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 05 — grep, find và wildcard**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-05.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 06 — Pipes, redirect, tee, xargs**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-06.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 07 — Mini challenge: truy tìm file và lọc log**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-07.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 1:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 02 — Users, permissions & processes

- [ ] **Ngày 08 — User, group, id, whoami**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-08.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 09 — chmod, chown, umask**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-09.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 10 — sudo, su và nguyên tắc least privilege**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-10.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 11 — ps, top, htop, kill, signals**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-11.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 12 — Jobs, foreground/background, nohup**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-12.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 13 — Environment variables, PATH, aliases**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-13.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 14 — Mini challenge: audit quyền truy cập**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-14.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 2:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 03 — Linux server operations

- [ ] **Ngày 15 — Package management apt, dpkg**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-15.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 16 — systemd, systemctl, journalctl**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-16.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 17 — SSH client/server và SSH keys**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-17.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 18 — Cron và systemd timers**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-18.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 19 — Disk: df, du, lsblk, mount**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-19.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 20 — Logs, logrotate và troubleshooting**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-20.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 21 — Mini challenge: vận hành service**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-21.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 3:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 04 — Networking foundations

- [ ] **Ngày 22 — OSI và TCP/IP**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-22.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 23 — IPv4, CIDR, subnetting**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-23.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 24 — TCP handshake, UDP, ports**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-24.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 25 — DNS: dig, nslookup**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-25.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 26 — HTTP methods, headers, status codes**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-26.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 27 — TLS, HTTPS, certificates**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-27.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 28 — Mini challenge: giải thích request end-to-end**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-28.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 4:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 05 — Linux networking tools

- [ ] **Ngày 29 — ip addr, ip route**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-29.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 30 — ss, lsof và listening ports**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-30.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 31 — ping, traceroute, mtr**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-31.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 32 — curl và kiểm tra API**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-32.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 33 — tcpdump cơ bản trong lab**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-33.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 34 — Wireshark và bộ lọc hiển thị**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-34.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 35 — Mini challenge: phân tích PCAP lab**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-35.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 5:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 06 — Bash & Python automation

- [ ] **Ngày 36 — Bash variables, quoting, exit codes**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-36.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 37 — if, case, loops, functions**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-37.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 38 — stdin, stdout, stderr và pipefail**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-38.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 39 — Regex, sed, awk cơ bản**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-39.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 40 — Python pathlib, argparse, subprocess**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-40.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 41 — Python đọc và tổng hợp log**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-41.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 42 — Mini project: log analyzer**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-42.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 6:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 07 — Security foundations

- [ ] **Ngày 43 — CIA triad, threat modeling**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-43.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 44 — Authentication vs authorization**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-44.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 45 — Hashing, encryption, secrets**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-45.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 46 — Linux permission threats**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-46.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 47 — Patch management, vulnerability lifecycle**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-47.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 48 — Security logging và detection**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-48.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 49 — Mini challenge: threat model API**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-49.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 7:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 08 — Web security I

- [ ] **Ngày 50 — OWASP Top 10 overview**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-50.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 51 — SQL injection: nguyên lý và phòng ngừa**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-51.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 52 — XSS: nguyên lý và output encoding**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-52.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 53 — CSRF và SameSite**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-53.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 54 — IDOR/BOLA và kiểm tra quyền**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-54.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 55 — Session, cookies, JWT**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-55.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 56 — Mini challenge: audit Spring Boot lab**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-56.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 8:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 09 — Web security II

- [ ] **Ngày 57 — Burp Suite proxy trên lab**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-57.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 58 — HTTP request/response inspection**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-58.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 59 — Input validation và deserialization risks**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-59.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 60 — File upload security**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-60.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 61 — Rate limiting và brute-force defenses**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-61.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 62 — CORS, CSP, security headers**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-62.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 63 — Mini challenge: viết security test cases**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-63.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 9:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 10 — Pentest methodology

- [ ] **Ngày 64 — Scope, rules of engagement, permission**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-64.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 65 — Asset inventory trong lab**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-65.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 66 — Nmap discovery trong lab**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-66.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 67 — Service enumeration trong lab**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-67.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 68 — Vulnerability triage và false positives**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-68.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 69 — Evidence, severity, remediation**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-69.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 70 — Mini assessment: báo cáo lab**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-70.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 10:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 11 — Linux & container hardening

- [ ] **Ngày 71 — SSH hardening trong VM**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-71.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 72 — UFW/nftables và rule review**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-72.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 73 — Audit users, sudoers, file permissions**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-73.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 74 — Docker images, rootless, capabilities**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-74.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 75 — Secrets và environment hygiene**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-75.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 76 — Backup, restore và incident basics**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-76.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 77 — Mini project: hardening checklist**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-77.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 11:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

### Tuần 12 — Capstone & portfolio

- [ ] **Ngày 78 — Thiết kế lab Ubuntu + web app**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-78.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 79 — Vẽ sơ đồ mạng và attack surface**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-79.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 80 — Threat model cho ứng dụng demo**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-80.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 81 — Chạy security checks có phạm vi**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-81.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 82 — Khắc phục ít nhất 3 vấn đề tìm thấy**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-82.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 83 — Viết báo cáo có evidence và retest**
  - Thực hành: Thực hiện ít nhất 3 thao tác hoặc phép thử trên máy lab, lưu lệnh và output; ghi 1 lỗi/edge case và cách kiểm chứng.
  - Bàn giao: `notes/day-83.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).
- [ ] **Ngày 84 — Demo capstone và retrospective**
  - Thực hành: Tự giải bài tổng hợp không xem đáp án, ghi lại bước làm, kết quả, lỗi và cách sửa.
  - Bàn giao: `notes/day-84.md` (mục tiêu, lệnh/thao tác, output, giải thích, câu hỏi còn lại).

**Đánh giá tuần 12:** Tự trình bày lại 3 kiến thức quan trọng, demo 1 thao tác và liệt kê 1 rủi ro bảo mật.

- [ ] **Ngày 85 — Review tổng hợp Linux**
  - Thực hành: Tự giải 15 nhiệm vụ terminal không xem ghi chú.
  - Bàn giao: `notes/day-85.md`.
- [ ] **Ngày 86 — Review networking**
  - Thực hành: Giải thích DNS → TCP → TLS → HTTP và phân tích một PCAP.
  - Bàn giao: `notes/day-86.md`.
- [ ] **Ngày 87 — Review web security**
  - Thực hành: Viết 10 test case auth/authz cho API demo.
  - Bàn giao: `notes/day-87.md`.
- [ ] **Ngày 88 — Final assessment**
  - Thực hành: Hoàn thành báo cáo pentest lab + kế hoạch 90 ngày tiếp theo.
  - Bàn giao: `notes/day-88.md`.
- [ ] **Ngày 89 — Portfolio publish**
  - Thực hành: Đưa README, script và báo cáo đã ẩn bí mật lên GitHub.
  - Bàn giao: `notes/day-89.md`.
- [ ] **Ngày 90 — Self evaluation**
  - Thực hành: Chấm mức tự chủ từng kỹ năng, chọn điểm yếu để luyện tiếp.
  - Bàn giao: `notes/day-90.md`.

## Mẫu ghi chép hằng ngày
```markdown
# Day XX — Chủ đề
## Mục tiêu
## Khái niệm cốt lõi (tự diễn giải)
## Lệnh / thao tác đã thử
## Kết quả và giải thích
## Lỗi gặp phải và cách debug
## Security implications
## Tự chấm (0–5) và câu hỏi còn lại
```

## Các mốc đánh giá
| Mốc | Bài kiểm tra | Điều kiện đạt |
|---|---|---|
| Ngày 30 | Quản trị Ubuntu Server VM, xử lý service và SSH | Tự làm, giải thích output và lỗi |
| Ngày 60 | Phân tích packet + script tổng hợp log | Script chạy được, có test dữ liệu lỗi |
| Ngày 90 | Audit web app + hardening Linux lab | Báo cáo evidence, impact, fix, retest |

## Tài nguyên
- Linux Journey: https://linuxjourney.com/
- OverTheWire Bandit: https://overthewire.org/wargames/bandit/
- Ubuntu Server docs: https://documentation.ubuntu.com/server/
- Wireshark docs: https://www.wireshark.org/docs/
- PortSwigger Academy: https://portswigger.net/web-security
- OWASP WSTG: https://owasp.org/www-project-web-security-testing-guide/
- OWASP Juice Shop: https://owasp.org/www-project-juice-shop/

## Sau 90 ngày
Tiếp tục 3–9 tháng với Linux internals, Active Directory lab, cloud security, secure code review, incident response, báo cáo chuyên nghiệp và thực hành được cấp phép.