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

---

# PHẦN MỞ RỘNG — NGÀY 91–540 (15 MODULE × 30 NGÀY)

> Đây là phần **bổ sung** cho kế hoạch 90 ngày phía trên, không thay thế các bài đã có. Tổng cộng **540 ngày (~18 tháng)**. Lịch học linh hoạt; ưu tiên đạt năng lực thay vì chạy theo số ngày.

## Phương pháp học và quy tắc lab
- **Mỗi ngày 60–120 phút:** 15–25 phút đọc, 40–75 phút lab, 10–20 phút ghi chú và tự kiểm tra.
- **Không xem lời giải trước:** tự đặt giả thuyết, chạy thử, lưu bằng chứng, giải thích kết quả và sửa sai.
- **Môi trường:** WSL2 Ubuntu cho CLI; Ubuntu Server VM, Windows evaluation VM và AD domain cô lập; web app dễ tổn thương chỉ chạy trong lab.
- **Phạm vi hợp pháp:** chỉ thao tác trên tài sản sở hữu hoặc được cấp phép rõ ràng. Các bài về tấn công chỉ thực hiện trong lab cố ý dễ tổn thương; không thử trên Internet.
- **An toàn:** tạo snapshot trước lab, không lưu credentials thực, không mở cổng lab dễ tổn thương ra Internet, đặt ngân sách cloud và xóa tài nguyên sau học.
- **Bằng chứng:** `notes/day-NNN.md`, gồm Mục tiêu / Mô hình / Lệnh hoặc bước / Output đã ẩn dữ liệu nhạy cảm / Giải thích / Rủi ro / Khắc phục / Tự đánh giá.
- **Điều kiện hoàn thành ngày:** tạo được bằng chứng, giải thích được cơ chế, chỉ ra ít nhất 1 trường hợp lỗi hoặc giới hạn.

## Năng lực sau từng chặng
| Mốc | Kết quả có thể chứng minh |
|---|---|
| 90 ngày | Linux cơ bản, networking, scripting, web security căn bản |
| 180 ngày | Linux internals, network troubleshooting, công cụ automation phòng thủ |
| 270 ngày | Đánh giá bảo mật Web/API, viết finding và đề xuất fix |
| 360 ngày | Windows/AD và cloud security căn bản trên lab cô lập |
| 450 ngày | Container/Kubernetes, detection/incident response, crypto, secure SDLC |
| 540 ngày | Portfolio chuyên sâu Web/API, báo cáo đánh giá và capstone tổng hợp |

## Cách chấm mỗi bài (0–5)
- **0:** chưa thực hiện; **1:** làm theo mẫu; **2:** tự chạy được; **3:** giải thích đúng; **4:** xử lý lỗi/edge case; **5:** có kiểm chứng, ghi lại trade-off và cách phòng vệ.
- Đạt **≥3/5** mới đánh dấu hoàn thành; các ngày capstone cần **≥4/5**.

## Module 01 — Ngày 91–120: Linux Internals nâng cao

- [ ] **Ngày 091 — Boot chain BIOS/UEFI, GRUB, kernel**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Boot chain BIOS/UEFI, GRUB, kernel**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-091.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 092 — initramfs và mount root**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **initramfs và mount root**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-092.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 093 — systemd targets và dependencies**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **systemd targets và dependencies**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-093.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 094 — systemd unit sandboxing**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **systemd unit sandboxing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-094.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 095 — /proc và /sys**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **/proc và /sys**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-095.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 096 — strace: system calls**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **strace: system calls**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-096.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 097 — lsof và file descriptors**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **lsof và file descriptors**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-097.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 098 — Signals và process states**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Signals và process states**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-098.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 099 — Namespaces: PID, mount, network**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Namespaces: PID, mount, network**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-099.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 100 — cgroups v2 resource limits**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **cgroups v2 resource limits**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-100.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 101 — Capabilities thay cho root**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Capabilities thay cho root**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-101.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 102 — PAM authentication**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **PAM authentication**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-102.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 103 — NSS và identity resolution**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **NSS và identity resolution**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-103.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 104 — ACL và umask**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **ACL và umask**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-104.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 105 — SUID/SGID/sticky bit audit**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **SUID/SGID/sticky bit audit**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-105.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 106 — AppArmor profiles**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **AppArmor profiles**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-106.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 107 — Kernel modules và sysctl**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Kernel modules và sysctl**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-107.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 108 — Virtual memory và swap**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Virtual memory và swap**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-108.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 109 — OOM killer và pressure**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **OOM killer và pressure**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-109.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 110 — Disk partitions và LVM**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Disk partitions và LVM**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-110.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 111 — Filesystem ext4 và inode**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Filesystem ext4 và inode**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-111.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 112 — Mount flags nosuid/nodev/noexec**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Mount flags nosuid/nodev/noexec**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-112.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 113 — Auditd events**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Auditd events**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-113.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 114 — Journald persistence**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Journald persistence**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-114.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 115 — Logrotate**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Logrotate**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-115.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 116 — Backup và restore test**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Backup và restore test**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-116.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 117 — Patch management**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Patch management**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-117.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 118 — System baseline**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **System baseline**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-118.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 119 — Incident triage trên Linux**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Incident triage trên Linux**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-119.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 120 — Capstone: Linux internals report**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: Linux internals report**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-120.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 01:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 02 — Ngày 121–150: Network Engineering nâng cao

- [ ] **Ngày 121 — OSI vs TCP/IP mapping**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **OSI vs TCP/IP mapping**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-121.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 122 — IPv4 subnetting drills**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **IPv4 subnetting drills**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-122.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 123 — IPv6 address types**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **IPv6 address types**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-123.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 124 — ARP và neighbor discovery**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **ARP và neighbor discovery**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-124.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 125 — Ethernet frames và VLAN**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Ethernet frames và VLAN**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-125.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 126 — Switching vs routing**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Switching vs routing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-126.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 127 — Static routing lab**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Static routing lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-127.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 128 — NAT/PAT và conntrack**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **NAT/PAT và conntrack**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-128.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 129 — TCP handshake và teardown**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **TCP handshake và teardown**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-129.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 130 — TCP retransmission/window**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **TCP retransmission/window**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-130.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 131 — UDP và ICMP**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **UDP và ICMP**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-131.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 132 — DNS recursion/cache**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **DNS recursion/cache**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-132.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 133 — DNSSEC concepts**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **DNSSEC concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-133.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 134 — DHCP lease lifecycle**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **DHCP lease lifecycle**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-134.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 135 — TLS handshake và certificates**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **TLS handshake và certificates**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-135.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 136 — PKI và certificate chain**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **PKI và certificate chain**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-136.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 137 — HTTP/1.1 vs HTTP/2**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **HTTP/1.1 vs HTTP/2**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-137.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 138 — HTTP/3 QUIC overview**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **HTTP/3 QUIC overview**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-138.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 139 — Reverse proxy và load balancing**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Reverse proxy và load balancing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-139.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 140 — VPN fundamentals**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **VPN fundamentals**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-140.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 141 — WireGuard lab**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **WireGuard lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-141.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 142 — Firewall stateful rules**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Firewall stateful rules**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-142.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 143 — nftables basics**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **nftables basics**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-143.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 144 — Packet capture filters**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Packet capture filters**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-144.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 145 — Wireshark TCP analysis**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Wireshark TCP analysis**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-145.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 146 — Network namespaces lab**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Network namespaces lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-146.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 147 — Network troubleshooting playbook**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Network troubleshooting playbook**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-147.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 148 — Traffic baselining**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Traffic baselining**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-148.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 149 — Threat modeling network paths**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Threat modeling network paths**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-149.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 150 — Capstone: segmented lab network**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: segmented lab network**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-150.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 02:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 03 — Ngày 151–180: Python & Bash Security Automation

- [ ] **Ngày 151 — Bash strict mode**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Bash strict mode**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-151.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 152 — Exit status và trap**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Exit status và trap**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-152.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 153 — Quoting và word splitting**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Quoting và word splitting**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-153.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 154 — Arrays và functions**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Arrays và functions**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-154.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 155 — Safe temp files**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Safe temp files**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-155.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 156 — ShellCheck lint**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **ShellCheck lint**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-156.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 157 — Cron vs systemd timer**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Cron vs systemd timer**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-157.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 158 — Parse journalctl output**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Parse journalctl output**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-158.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 159 — Regex log extraction**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Regex log extraction**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-159.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 160 — Python venv và packaging**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Python venv và packaging**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-160.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 161 — argparse CLI**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **argparse CLI**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-161.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 162 — pathlib và file IO**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **pathlib và file IO**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-162.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 163 — json/csv parsing**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **json/csv parsing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-163.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 164 — Requests HTTP client**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Requests HTTP client**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-164.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 165 — Timeout/retry/backoff**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Timeout/retry/backoff**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-165.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 166 — Python logging**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Python logging**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-166.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 167 — Unit test pytest**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Unit test pytest**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-167.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 168 — Mocking external services**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Mocking external services**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-168.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 169 — Socket client localhost**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Socket client localhost**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-169.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 170 — TLS certificate inspection**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **TLS certificate inspection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-170.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 171 — Hashing files SHA-256**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Hashing files SHA-256**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-171.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 172 — HMAC concepts**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **HMAC concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-172.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 173 — Secrets via environment**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Secrets via environment**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-173.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 174 — Safe subprocess usage**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Safe subprocess usage**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-174.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 175 — Rate limiting scripts**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Rate limiting scripts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-175.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 176 — Concurrent log processing**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Concurrent log processing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-176.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 177 — SQLite evidence storage**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **SQLite evidence storage**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-177.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 178 — Generate Markdown report**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Generate Markdown report**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-178.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 179 — CI checks for tool**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **CI checks for tool**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-179.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 180 — Capstone: defensive audit CLI**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: defensive audit CLI**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-180.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 03:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 04 — Ngày 181–210: Web Security & OWASP chuyên sâu

- [ ] **Ngày 181 — HTTP request anatomy**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **HTTP request anatomy**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-181.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 182 — Cookies Secure/HttpOnly/SameSite**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Cookies Secure/HttpOnly/SameSite**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-182.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 183 — Session lifecycle**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Session lifecycle**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-183.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 184 — JWT validation pitfalls**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **JWT validation pitfalls**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-184.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 185 — OAuth2 flows**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **OAuth2 flows**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-185.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 186 — OIDC ID token checks**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **OIDC ID token checks**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-186.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 187 — Access control matrix**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Access control matrix**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-187.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 188 — IDOR/BOLA lab**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **IDOR/BOLA lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-188.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 189 — Broken function authorization**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Broken function authorization**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-189.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 190 — SQL injection lab**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **SQL injection lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-190.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 191 — Parameterized query fix**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Parameterized query fix**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-191.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 192 — XSS reflected lab**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **XSS reflected lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-192.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 193 — XSS stored lab**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **XSS stored lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-193.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 194 — CSP defense**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **CSP defense**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-194.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 195 — CSRF token and SameSite**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **CSRF token and SameSite**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-195.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 196 — SSRF concept and lab**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **SSRF concept and lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-196.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 197 — Path traversal lab**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Path traversal lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-197.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 198 — File upload validation**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **File upload validation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-198.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 199 — Command injection lab**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Command injection lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-199.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 200 — Template injection concepts**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Template injection concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-200.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 201 — Deserialization risks**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Deserialization risks**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-201.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 202 — Security misconfiguration**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Security misconfiguration**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-202.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 203 — CORS configuration**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **CORS configuration**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-203.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 204 — Rate limiting and abuse**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Rate limiting and abuse**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-204.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 205 — Business logic flaws**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Business logic flaws**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-205.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 206 — Password reset security**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Password reset security**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-206.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 207 — MFA threat modeling**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **MFA threat modeling**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-207.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 208 — Error handling/info disclosure**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Error handling/info disclosure**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-208.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 209 — Secure headers and TLS**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Secure headers and TLS**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-209.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 210 — Capstone: OWASP assessment**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: OWASP assessment**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-210.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 04:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 05 — Ngày 211–240: API & Java Security

- [ ] **Ngày 211 — REST authn/authz review**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **REST authn/authz review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-211.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 212 — Spring Security filter chain**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Spring Security filter chain**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-212.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 213 — Method-level authorization**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Method-level authorization**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-213.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 214 — Multi-tenant data isolation**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Multi-tenant data isolation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-214.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 215 — BOLA tests**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **BOLA tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-215.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 216 — Mass assignment protection**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Mass assignment protection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-216.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 217 — DTO validation**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **DTO validation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-217.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 218 — Bean Validation boundaries**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Bean Validation boundaries**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-218.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 219 — SQL/JPA query security**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **SQL/JPA query security**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-219.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 220 — Optimistic locking**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Optimistic locking**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-220.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 221 — Race conditions in transfers**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Race conditions in transfers**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-221.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 222 — Idempotency keys**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Idempotency keys**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-222.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 223 — Replay prevention**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Replay prevention**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-223.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 224 — JWT key rotation**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **JWT key rotation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-224.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 225 — Refresh token lifecycle**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Refresh token lifecycle**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-225.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 226 — OAuth2 redirect validation**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **OAuth2 redirect validation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-226.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 227 — TOTP enrollment protection**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **TOTP enrollment protection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-227.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 228 — CORS for SPA**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **CORS for SPA**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-228.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 229 — CSRF with cookies**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **CSRF with cookies**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-229.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 230 — Upload malware safeguards**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Upload malware safeguards**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-230.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 231 — Content-type sniffing**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Content-type sniffing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-231.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 232 — API pagination abuse**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **API pagination abuse**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-232.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 233 — Rate limit design**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Rate limit design**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-233.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 234 — Audit log integrity**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Audit log integrity**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-234.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 235 — Sensitive data masking**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Sensitive data masking**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-235.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 236 — Secrets management**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Secrets management**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-236.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 237 — Dependency CVE review**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Dependency CVE review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-237.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 238 — SAST and dependency scanning**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **SAST and dependency scanning**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-238.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 239 — Integration security tests**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Integration security tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-239.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 240 — Capstone: secure Spring Boot API**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: secure Spring Boot API**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-240.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 05:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 06 — Ngày 241–270: Pentest Methodology & Tooling

- [ ] **Ngày 241 — Authorization and scope**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Authorization and scope**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-241.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 242 — Rules of engagement**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Rules of engagement**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-242.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 243 — Asset inventory lab**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Asset inventory lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-243.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 244 — Threat modeling STRIDE**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Threat modeling STRIDE**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-244.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 245 — Attack surface mapping**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Attack surface mapping**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-245.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 246 — Nmap TCP localhost lab**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Nmap TCP localhost lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-246.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 247 — Nmap UDP controlled lab**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Nmap UDP controlled lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-247.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 248 — Service version verification**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Service version verification**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-248.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 249 — False positive handling**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **False positive handling**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-249.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 250 — Burp proxy setup**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Burp proxy setup**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-250.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 251 — Repeater request comparison**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Repeater request comparison**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-251.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 252 — Browser devtools security**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Browser devtools security**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-252.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 253 — Authenticated test accounts**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Authenticated test accounts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-253.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 254 — Role matrix testing**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Role matrix testing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-254.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 255 — API schema enumeration**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **API schema enumeration**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-255.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 256 — Input validation tests**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Input validation tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-256.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 257 — Session management tests**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Session management tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-257.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 258 — Password policy review**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Password policy review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-258.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 259 — Security headers assessment**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Security headers assessment**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-259.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 260 — TLS configuration review**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **TLS configuration review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-260.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 261 — Evidence collection hygiene**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Evidence collection hygiene**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-261.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 262 — Severity vs exploitability**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Severity vs exploitability**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-262.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 263 — CVSS basics**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **CVSS basics**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-263.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 264 — Risk prioritization**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Risk prioritization**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-264.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 265 — Reproduction steps**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Reproduction steps**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-265.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 266 — Remediation guidance**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Remediation guidance**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-266.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 267 — Retest methodology**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Retest methodology**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-267.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 268 — Executive summary writing**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Executive summary writing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-268.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 269 — Technical report writing**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Technical report writing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-269.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 270 — Capstone: scoped lab pentest**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: scoped lab pentest**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-270.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 06:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 07 — Ngày 271–300: Windows Fundamentals & Security

- [ ] **Ngày 271 — Windows filesystem and registry**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Windows filesystem and registry**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-271.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 272 — Users/groups and UAC**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Users/groups and UAC**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-272.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 273 — PowerShell basics**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **PowerShell basics**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-273.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 274 — Services and scheduled tasks**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Services and scheduled tasks**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-274.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 275 — Windows Event Logs**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Windows Event Logs**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-275.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 276 — Event IDs login basics**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Event IDs login basics**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-276.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 277 — NTFS ACLs**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **NTFS ACLs**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-277.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 278 — Windows Defender overview**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Windows Defender overview**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-278.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 279 — Windows Firewall**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Windows Firewall**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-279.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 280 — Windows networking tools**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Windows networking tools**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-280.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 281 — SMB concepts**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **SMB concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-281.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 282 — RDP hardening**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **RDP hardening**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-282.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 283 — Windows updates**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Windows updates**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-283.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 284 — Local security policy**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Local security policy**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-284.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 285 — Credential storage concepts**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Credential storage concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-285.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 286 — Kerberos overview**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Kerberos overview**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-286.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 287 — NTLM overview**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **NTLM overview**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-287.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 288 — Windows process inspection**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Windows process inspection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-288.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 289 — Sysmon installation lab**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Sysmon installation lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-289.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 290 — Sysmon event analysis**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Sysmon event analysis**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-290.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 291 — PowerShell script signing**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **PowerShell script signing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-291.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 292 — PowerShell logging**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **PowerShell logging**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-292.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 293 — AppLocker/WDAC concepts**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **AppLocker/WDAC concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-293.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 294 — Remote management WinRM**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Remote management WinRM**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-294.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 295 — Windows backup restore**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Windows backup restore**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-295.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 296 — Local privilege boundaries**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Local privilege boundaries**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-296.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 297 — Patch audit**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Patch audit**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-297.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 298 — Windows hardening checklist**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Windows hardening checklist**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-298.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 299 — Triage suspicious event lab**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Triage suspicious event lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-299.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 300 — Capstone: Windows audit report**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: Windows audit report**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-300.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 07:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 08 — Ngày 301–330: Active Directory Security Lab

- [ ] **Ngày 301 — AD domain structure**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **AD domain structure**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-301.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 302 — Domain controller setup isolated**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Domain controller setup isolated**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-302.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 303 — DNS in Active Directory**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **DNS in Active Directory**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-303.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 304 — Organizational Units**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Organizational Units**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-304.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 305 — Users/groups/GPO**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Users/groups/GPO**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-305.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 306 — Least privilege roles**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Least privilege roles**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-306.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 307 — Kerberos ticket flow**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Kerberos ticket flow**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-307.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 308 — NTLM vs Kerberos**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **NTLM vs Kerberos**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-308.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 309 — LDAP and LDAPS**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **LDAP and LDAPS**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-309.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 310 — Group Policy application**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Group Policy application**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-310.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 311 — Service accounts**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Service accounts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-311.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 312 — Managed service accounts**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Managed service accounts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-312.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 313 — SPN concepts**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **SPN concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-313.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 314 — AD trust concepts**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **AD trust concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-314.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 315 — Delegation concepts**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Delegation concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-315.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 316 — ACL and object permissions**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **ACL and object permissions**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-316.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 317 — Password and lockout policies**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Password and lockout policies**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-317.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 318 — LAPS overview**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **LAPS overview**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-318.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 319 — Tiered administration**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Tiered administration**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-319.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 320 — Privileged access workstations**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Privileged access workstations**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-320.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 321 — Audit directory changes**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Audit directory changes**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-321.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 322 — Windows event correlation**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Windows event correlation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-322.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 323 — Identity inventory**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Identity inventory**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-323.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 324 — Secure LDAP config**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Secure LDAP config**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-324.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 325 — GPO security baseline**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **GPO security baseline**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-325.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 326 — Detect risky permissions**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Detect risky permissions**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-326.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 327 — AD backup planning**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **AD backup planning**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-327.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 328 — Restore test lab**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Restore test lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-328.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 329 — AD threat modeling**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **AD threat modeling**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-329.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 330 — Capstone: AD security assessment**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: AD security assessment**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-330.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 08:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 09 — Ngày 331–360: Cloud Security AWS/Azure

- [ ] **Ngày 331 — Shared responsibility model**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Shared responsibility model**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-331.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 332 — IAM users roles policies**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **IAM users roles policies**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-332.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 333 — Least privilege IAM lab**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Least privilege IAM lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-333.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 334 — MFA and root account protection**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **MFA and root account protection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-334.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 335 — Cloud audit logging**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Cloud audit logging**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-335.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 336 — VPC and subnets**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **VPC and subnets**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-336.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 337 — Security groups vs NACL**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Security groups vs NACL**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-337.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 338 — Public vs private networking**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Public vs private networking**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-338.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 339 — S3 bucket access controls**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **S3 bucket access controls**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-339.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 340 — Encryption at rest**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Encryption at rest**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-340.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 341 — KMS fundamentals**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **KMS fundamentals**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-341.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 342 — Secrets Manager patterns**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Secrets Manager patterns**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-342.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 343 — Compute instance hardening**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Compute instance hardening**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-343.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 344 — Metadata service IMDSv2**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Metadata service IMDSv2**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-344.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 345 — Cloud load balancer TLS**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Cloud load balancer TLS**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-345.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 346 — Cloud WAF concepts**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Cloud WAF concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-346.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 347 — CloudTrail analysis**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **CloudTrail analysis**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-347.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 348 — GuardDuty concepts**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **GuardDuty concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-348.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 349 — Cloud cost and budgets**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Cloud cost and budgets**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-349.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 350 — Infrastructure as Code basics**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Infrastructure as Code basics**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-350.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 351 — Terraform plan review**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Terraform plan review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-351.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 352 — IaC misconfiguration checks**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **IaC misconfiguration checks**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-352.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 353 — CI/CD cloud credentials**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **CI/CD cloud credentials**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-353.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 354 — OIDC federation for CI**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **OIDC federation for CI**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-354.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 355 — Container registry scanning**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Container registry scanning**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-355.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 356 — Backup and recovery**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Backup and recovery**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-356.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 357 — Cloud incident response**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Cloud incident response**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-357.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 358 — Azure Entra ID basics**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Azure Entra ID basics**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-358.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 359 — Multi-cloud differences**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Multi-cloud differences**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-359.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 360 — Capstone: cloud security baseline**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: cloud security baseline**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-360.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 09:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 10 — Ngày 361–390: Containers & Kubernetes Security

- [ ] **Ngày 361 — Docker namespaces/cgroups review**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Docker namespaces/cgroups review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-361.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 362 — Dockerfile least privilege**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Dockerfile least privilege**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-362.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 363 — Multi-stage builds**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Multi-stage builds**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-363.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 364 — Minimal base images**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Minimal base images**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-364.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 365 — Image scanning**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Image scanning**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-365.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 366 — SBOM concepts**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **SBOM concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-366.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 367 — Image signing**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Image signing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-367.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 368 — Secrets in containers**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Secrets in containers**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-368.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 369 — Read-only filesystem**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Read-only filesystem**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-369.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 370 — Linux capabilities in Docker**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Linux capabilities in Docker**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-370.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 371 — Seccomp and AppArmor**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Seccomp and AppArmor**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-371.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 372 — Network isolation in Compose**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Network isolation in Compose**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-372.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 373 — Docker socket risks**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Docker socket risks**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-373.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 374 — Container logging**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Container logging**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-374.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 375 — Supply chain dependency risk**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Supply chain dependency risk**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-375.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 376 — Kubernetes architecture**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Kubernetes architecture**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-376.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 377 — Pods deployments services**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Pods deployments services**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-377.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 378 — Kubernetes RBAC**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Kubernetes RBAC**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-378.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 379 — ServiceAccount tokens**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **ServiceAccount tokens**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-379.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 380 — NetworkPolicy lab**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **NetworkPolicy lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-380.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 381 — Pod Security Standards**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Pod Security Standards**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-381.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 382 — Admission controls**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Admission controls**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-382.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 383 — Secrets management in K8s**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Secrets management in K8s**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-383.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 384 — etcd security overview**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **etcd security overview**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-384.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 385 — Ingress TLS**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Ingress TLS**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-385.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 386 — Resource quotas**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Resource quotas**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-386.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 387 — Kubernetes audit logs**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Kubernetes audit logs**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-387.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 388 — Cluster upgrade planning**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Cluster upgrade planning**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-388.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 389 — K8s incident triage**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **K8s incident triage**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-389.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 390 — Capstone: container threat model**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: container threat model**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-390.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 10:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 11 — Ngày 391–420: Detection Engineering & DFIR

- [ ] **Ngày 391 — Security telemetry sources**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Security telemetry sources**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-391.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 392 — Log collection pipeline**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Log collection pipeline**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-392.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 393 — Normalization and timestamps**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Normalization and timestamps**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-393.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 394 — MITRE ATT&CK mapping**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **MITRE ATT&CK mapping**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-394.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 395 — Detection rule structure**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Detection rule structure**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-395.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 396 — Sigma basics**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Sigma basics**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-396.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 397 — False positive tuning**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **False positive tuning**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-397.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 398 — Linux auth log detections**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Linux auth log detections**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-398.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 399 — SSH brute force detection**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **SSH brute force detection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-399.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 400 — Web auth anomaly detection**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Web auth anomaly detection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-400.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 401 — API abuse detection**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **API abuse detection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-401.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 402 — Windows login detections**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Windows login detections**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-402.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 403 — Sysmon process events**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Sysmon process events**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-403.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 404 — DNS anomaly patterns**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **DNS anomaly patterns**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-404.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 405 — Network flow monitoring**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Network flow monitoring**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-405.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 406 — Alert severity and triage**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Alert severity and triage**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-406.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 407 — Incident classification**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Incident classification**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-407.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 408 — Evidence chain of custody**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Evidence chain of custody**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-408.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 409 — Disk image concepts**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Disk image concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-409.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 410 — Memory forensics overview**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Memory forensics overview**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-410.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 411 — Timeline construction**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Timeline construction**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-411.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 412 — IOC vs behavior detection**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **IOC vs behavior detection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-412.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 413 — Containment decisions**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Containment decisions**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-413.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 414 — Eradication and recovery**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Eradication and recovery**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-414.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 415 — Post-incident review**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Post-incident review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-415.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 416 — Tabletop exercise**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Tabletop exercise**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-416.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 417 — Detection unit tests**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Detection unit tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-417.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 418 — Metrics precision/recall**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Metrics precision/recall**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-418.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 419 — Runbook writing**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Runbook writing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-419.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 420 — Capstone: incident response simulation**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: incident response simulation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-420.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 11:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 12 — Ngày 421–450: Cryptography & Secure Protocols

- [ ] **Ngày 421 — Threat models for crypto**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Threat models for crypto**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-421.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 422 — Symmetric vs asymmetric**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Symmetric vs asymmetric**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-422.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 423 — AES modes and nonce**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **AES modes and nonce**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-423.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 424 — AEAD AES-GCM**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **AEAD AES-GCM**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-424.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 425 — Hash vs encryption**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Hash vs encryption**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-425.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 426 — Password hashing Argon2/bcrypt**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Password hashing Argon2/bcrypt**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-426.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 427 — Salt vs pepper**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Salt vs pepper**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-427.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 428 — HMAC and integrity**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **HMAC and integrity**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-428.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 429 — Digital signatures**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Digital signatures**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-429.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 430 — Key exchange basics**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Key exchange basics**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-430.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 431 — TLS 1.3 handshake**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **TLS 1.3 handshake**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-431.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 432 — Certificate chain verification**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Certificate chain verification**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-432.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 433 — Certificate revocation**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Certificate revocation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-433.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 434 — PKI operations**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **PKI operations**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-434.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 435 — Key rotation**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Key rotation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-435.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 436 — Secret storage**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Secret storage**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-436.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 437 — Entropy and CSPRNG**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Entropy and CSPRNG**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-437.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 438 — Replay attacks and nonce**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Replay attacks and nonce**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-438.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 439 — Timing attacks concept**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Timing attacks concept**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-439.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 440 — Constant-time comparison**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Constant-time comparison**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-440.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 441 — JWT signing algorithms**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **JWT signing algorithms**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-441.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 442 — JWE vs JWS**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **JWE vs JWS**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-442.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 443 — OAuth PKCE**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **OAuth PKCE**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-443.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 444 — TOTP/HOTP fundamentals**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **TOTP/HOTP fundamentals**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-444.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 445 — Secure session cookies**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Secure session cookies**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-445.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 446 — Data-at-rest encryption**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Data-at-rest encryption**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-446.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 447 — Backup encryption**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Backup encryption**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-447.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 448 — Cryptographic agility**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Cryptographic agility**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-448.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 449 — Crypto implementation review**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Crypto implementation review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-449.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 450 — Capstone: protocol security review**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: protocol security review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-450.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 12:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 13 — Ngày 451–480: Secure SDLC & Supply Chain

- [ ] **Ngày 451 — Threat modeling workflow**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Threat modeling workflow**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-451.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 452 — Secure coding standards**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Secure coding standards**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-452.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 453 — Security requirements**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Security requirements**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-453.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 454 — Architecture risk review**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Architecture risk review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-454.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 455 — SAST concepts**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **SAST concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-455.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 456 — SCA dependency checks**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **SCA dependency checks**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-456.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 457 — SBOM generation**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **SBOM generation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-457.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 458 — Dependency pinning**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Dependency pinning**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-458.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 459 — Artifact integrity**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Artifact integrity**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-459.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 460 — Build provenance**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Build provenance**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-460.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 461 — CI secret scanning**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **CI secret scanning**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-461.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 462 — Branch protection**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Branch protection**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-462.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 463 — Code review security**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Code review security**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-463.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 464 — Security unit tests**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Security unit tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-464.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 465 — DAST in staging**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **DAST in staging**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-465.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 466 — Container image policy**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Container image policy**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-466.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 467 — IaC scanning**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **IaC scanning**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-467.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 468 — Vulnerability disclosure policy**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Vulnerability disclosure policy**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-468.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 469 — CVE/CWE interpretation**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **CVE/CWE interpretation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-469.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 470 — CVSS prioritization**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **CVSS prioritization**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-470.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 471 — Patch SLA**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Patch SLA**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-471.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 472 — Security regression tests**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Security regression tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-472.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 473 — Abuse case tests**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Abuse case tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-473.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 474 — Fuzzing fundamentals**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Fuzzing fundamentals**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-474.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 475 — Property-based testing**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Property-based testing**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-475.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 476 — Secrets rotation playbook**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Secrets rotation playbook**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-476.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 477 — Release security checklist**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Release security checklist**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-477.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 478 — Incident readiness**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Incident readiness**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-478.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 479 — Security champions model**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Security champions model**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-479.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 480 — Capstone: secure delivery pipeline**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: secure delivery pipeline**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-480.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 13:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 14 — Ngày 481–510: Specialization: Web/API Pentest

- [ ] **Ngày 481 — Scope a complex web lab**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Scope a complex web lab**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-481.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 482 — Architecture diagram**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Architecture diagram**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-482.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 483 — Auth flows inventory**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Auth flows inventory**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-483.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 484 — Role permission matrix**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Role permission matrix**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-484.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 485 — Tenant isolation test plan**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Tenant isolation test plan**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-485.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 486 — Business logic modeling**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Business logic modeling**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-486.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 487 — API endpoint inventory**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **API endpoint inventory**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-487.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 488 — GraphQL security concepts**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **GraphQL security concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-488.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 489 — WebSocket security concepts**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **WebSocket security concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-489.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 490 — File handling threat model**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **File handling threat model**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-490.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 491 — SSRF mitigation review**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **SSRF mitigation review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-491.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 492 — Server-side validation**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Server-side validation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-492.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 493 — Race condition test design**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Race condition test design**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-493.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 494 — Rate limit bypass resistance**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Rate limit bypass resistance**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-494.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 495 — OAuth/OIDC configuration review**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **OAuth/OIDC configuration review**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-495.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 496 — SAML concepts**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **SAML concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-496.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 497 — Session fixation tests**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Session fixation tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-497.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 498 — Password recovery tests**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Password recovery tests**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-498.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 499 — MFA bypass resistance**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **MFA bypass resistance**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-499.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 500 — Sensitive data exposure**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Sensitive data exposure**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-500.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 501 — Cache poisoning concepts**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Cache poisoning concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-501.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 502 — HTTP request smuggling concepts**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **HTTP request smuggling concepts**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-502.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 503 — Host header validation**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Host header validation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-503.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 504 — CORS exploitability assessment**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **CORS exploitability assessment**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-504.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 505 — Cloud-backed web threats**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Cloud-backed web threats**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-505.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 506 — Containerized app attack surface**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Containerized app attack surface**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-506.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 507 — Secure code review Java**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Secure code review Java**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-507.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 508 — Write reproducible findings**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Write reproducible findings**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-508.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 509 — Retest after fixes**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Retest after fixes**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-509.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 510 — Capstone: complete web/API report**
  - **Bài thực hành:** Tự thiết kế bài kiểm tra tổng hợp, thực hiện, lập báo cáo bằng chứng và đề xuất cải thiện về **Capstone: complete web/API report**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-510.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 14:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Module 15 — Ngày 511–540: Portfolio, Certification & Career

- [ ] **Ngày 511 — Choose target role and scope**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Choose target role and scope**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-511.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 512 — Build home lab diagram**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Build home lab diagram**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-512.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 513 — Document Linux project**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Document Linux project**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-513.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 514 — Document network project**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Document network project**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-514.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 515 — Document API security project**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Document API security project**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-515.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 516 — Document cloud project**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Document cloud project**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-516.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 517 — Create anonymized case studies**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Create anonymized case studies**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-517.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 518 — Security report template**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Security report template**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-518.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 519 — Executive summary practice**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Executive summary practice**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-519.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 520 — Threat model portfolio**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Threat model portfolio**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-520.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 521 — Detection engineering portfolio**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Detection engineering portfolio**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-521.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 522 — GitHub repository hygiene**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **GitHub repository hygiene**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-522.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 523 — README and reproducibility**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **README and reproducibility**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-523.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 524 — Interview Linux scenarios**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Interview Linux scenarios**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-524.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 525 — Interview networking scenarios**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Interview networking scenarios**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-525.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 526 — Interview OWASP scenarios**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Interview OWASP scenarios**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-526.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 527 — Interview IAM scenarios**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Interview IAM scenarios**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-527.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 528 — Interview incident response**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Interview incident response**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-528.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 529 — Mock pentest scoping call**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Mock pentest scoping call**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-529.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 530 — Mock report presentation**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Mock report presentation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-530.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 531 — Map skills to eJPT objectives**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Map skills to eJPT objectives**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-531.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 532 — Map skills to PNPT/OSCP objectives**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Map skills to PNPT/OSCP objectives**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-532.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 533 — Choose realistic certification**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Choose realistic certification**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-533.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 534 — Create revision backlog**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Create revision backlog**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-534.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 535 — Timed lab challenge 1**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **Timed lab challenge 1**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-535.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 536 — Timed lab challenge 2**
  - **Bài thực hành:** Dựng mô hình và kiểm chứng về **Timed lab challenge 2**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-536.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 537 — Full-scope lab assessment**
  - **Bài thực hành:** Thực hiện lab cô lập, quan sát và giải thích về **Full-scope lab assessment**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-537.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 538 — Review all weak topics**
  - **Bài thực hành:** So sánh cấu hình an toàn/không an toàn trong lab về **Review all weak topics**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-538.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 539 — Final capstone defense/presentation**
  - **Bài thực hành:** Viết test hoặc checklist kiểm chứng về **Final capstone defense/presentation**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-539.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.
- [ ] **Ngày 540 — 12-month continuing learning plan**
  - **Bài thực hành:** Điều tra một lỗi giả lập và ghi cách khắc phục về **12-month continuing learning plan**; không sao chép đáp án.
  - **Bàn giao:** `notes/day-540.md` + lệnh/cấu hình/test đã ẩn bí mật + 1 edge case và cách xác minh.

**Checkpoint module 15:** Demo một kịch bản từ module, giải thích nguyên lý, rủi ro, biện pháp giảm thiểu và nộp báo cáo ngắn.

## Các dự án portfolio bắt buộc
1. **Linux Security Baseline:** Ubuntu Server VM, users/SSH/UFW/AppArmor/audit logs, rollback và báo cáo trước/sau.
2. **Network Troubleshooting Lab:** 2–3 VM, phân đoạn mạng, packet capture, tài liệu TCP/DNS/TLS.
3. **Defensive Automation CLI:** Python/Bash đọc log, phát hiện mẫu bất thường, test dữ liệu lỗi, xuất Markdown.
4. **Spring Boot API Security:** kiểm thử quyền truy cập đa tenant, JWT/refresh, rate limit, idempotency, race condition và regression tests.
5. **Windows/AD Lab:** mô hình domain cô lập, chính sách quyền tối thiểu, logging và hardening.
6. **Cloud/Container Security:** môi trường thử nghiệm có ngân sách, IAM tối thiểu, Docker/K8s policy, scanning và báo cáo.
7. **Pentest Report:** xác định phạm vi, bằng chứng đã làm sạch, mức độ rủi ro, cách tái hiện trên lab, fix và retest.
8. **Incident Response Exercise:** kịch bản giả lập, detection rules, timeline, runbook, postmortem.

## Tài liệu và chuẩn tham khảo mở rộng
- Linux man pages: https://man7.org/linux/man-pages/
- Linux kernel docs: https://docs.kernel.org/
- Red Hat system administration: https://docs.redhat.com/
- Nmap reference: https://nmap.org/book/man.html
- Wireshark documentation: https://www.wireshark.org/docs/
- OWASP WSTG: https://owasp.org/www-project-web-security-testing-guide/
- OWASP API Security: https://owasp.org/API-Security/
- PortSwigger Web Security Academy: https://portswigger.net/web-security
- Microsoft Learn security: https://learn.microsoft.com/security/
- AWS security documentation: https://docs.aws.amazon.com/security/
- Kubernetes security: https://kubernetes.io/docs/concepts/security/
- MITRE ATT&CK: https://attack.mitre.org/
- NIST Cybersecurity Framework: https://www.nist.gov/cyberframework
- OverTheWire: https://overthewire.org/wargames/

## Sau ngày 540: chọn chuyên môn, không cố học mọi thứ
- **Web/API Pentester / AppSec:** đào sâu business logic, secure code review, auth, cloud-backed APIs.
- **Linux/Cloud Security Engineer:** kernel, IAM, Kubernetes, detection, automation, hardening.
- **Red Team:** bổ sung kiến thức enterprise identity, adversary emulation được cấp phép, reporting và phối hợp Blue Team.
- **Reverse Engineering/Malware Analysis:** cần một lộ trình chuyên biệt bổ sung về C, assembly, binary formats, debugger, OS internals và phân tích mẫu an toàn.

**Ghi chú:** Hoàn thành checklist không tự động biến bạn thành chuyên gia. Chất lượng lab, khả năng tự giải thích, báo cáo và kinh nghiệm thực tế mới là thước đo chính.
