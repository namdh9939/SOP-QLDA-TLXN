# 📋 SOP Bộ Phận Quản Lý Dự Án — Trợ Lý Xây Nhà (TLXN)

### Công ty TNHH TM DV & XD Nhà Của Mình AC

> *"Chúng tôi không chọn lợi ích ngắn hạn. Chúng tôi chọn cấu trúc minh bạch để bảo vệ lợi ích dài hạn của tất cả các bên."*

---

## 🎯 Mục Đích

Tài liệu này hệ thống hóa toàn bộ **Quy trình vận hành chuẩn (SOP)** cho bộ phận Quản lý Dự án, bao gồm 4 vai trò chính:

| Vai trò                              | Mô tả                                                                                  | Emoji |
| ------------------------------------- | ---------------------------------------------------------------------------------------- | ----- |
| **PM** (Project Manager)        | Quản lý dự án — điều phối tổng thể, lập kế hoạch, "single point of contact" | 🎯    |
| **Account** (Account Manager)   | Đầu mối tiếp nhận yêu cầu KH, chăm sóc thường trực, kết nối đối tác     | 🤝    |
| **AA** (Architect Assistant)    | Trợ lý thiết kế — kiểm soát kiến trúc, phối hợp thiết kế                    | 📐    |
| **CA** (Construction Assistant) | Trợ lý công trình — giám sát hiện trường, nghiệm thu thi công                | 🔨    |

---

## 🗺️ Mindmap Tổng Quan

```
📁 SOP-QLDA-TLXN/
│
├── 📁 00-TONG-QUAN/                    ← Bạn đang ở đây
│   ├── flow-tong-the-du-an.md           Flow end-to-end từ Sale → Đóng DA
│   ├── ma-tran-RACI.md                  Ai làm gì (PM/AA/CA/Account)
│   ├── stakeholder-map.md               Bản đồ các bên liên quan
│   ├── cac-goi-dich-vu.md               3 gói: QTDA / TLXN / TLXN Từ Xa
│   └── thuat-ngu.md                     Giải thích thuật ngữ
│
├── 📁 01-PHOI-HOP-SALE-QLDA/           ← Quy trình chuyển giao từ Sale
│   ├── quy-trinh-ban-giao-tu-sale.md
│   ├── hop-kickoff-du-an.md
│   ├── tieu-chi-tiep-nhan-du-an.md
│   └── xu-ly-thong-tin-thieu.md
│
├── 📁 02-ACCOUNT/                       ← SOP cho Account Manager
│   ├── vai-tro-trach-nhiem.md
│   ├── tiep-nhan-thong-tin-khach-hang.md
│   ├── quan-ly-quan-he-khach-hang.md
│   ├── bao-cao-tinh-hinh-cho-khach.md
│   ├── xu-ly-khieu-nai-khach-hang.md
│   ├── upsell-va-gia-han-dich-vu.md
│   └── ban-giao-lai-khi-ket-thuc.md
│
├── 📁 03-PM/                            ← SOP cho Project Manager
│   ├── vai-tro-trach-nhiem.md
│   ├── tiep-nhan-du-an-tu-kickoff.md
│   ├── bo-nhiem-nhan-su-AA-CA.md
│   ├── lap-ke-hoach-du-an.md
│   ├── quan-ly-tien-do.md
│   ├── quan-ly-ngan-sach-thu-chi.md
│   ├── quan-ly-chat-luong.md
│   ├── quan-ly-rui-ro-va-van-de.md
│   ├── quan-ly-thay-doi-phat-sinh.md
│   ├── bao-cao-review-dinh-ky.md
│   ├── nghiem-thu-ban-giao.md
│   └── dong-du-an.md
│
├── 📁 04-AA/                            ← SOP cho Architect Assistant
│   ├── vai-tro-trach-nhiem.md
│   ├── quan-ly-ho-so-tai-lieu.md
│   ├── nhap-lieu-thu-chi.md
│   ├── soan-va-gui-bao-cao.md
│   ├── dieu-phoi-lich-hop.md
│   ├── phoi-hop-kiem-tra-thiet-ke.md
│   └── ho-tro-PM-ve-hanh-chinh.md
│
├── 📁 05-CA/                            ← SOP cho Construction Assistant
│   ├── vai-tro-trach-nhiem.md
│   ├── giam-sat-cong-truong.md
│   ├── kiem-tra-chat-luong-thi-cong.md
│   ├── bao-cao-hien-truong.md
│   ├── nghiem-thu-hang-muc.md
│   ├── xu-ly-su-co-cong-truong.md
│   └── 📁 checklist-nghiem-thu/          ← 49 Checklist theo hạng mục
│       ├── README.md
│       ├── 📁 phan-tho/
│       ├── 📁 hoan-thien/
│       ├── 📁 cua-va-vach/
│       ├── 📁 co-dien/
│       └── 📁 thiet-bi/
│
├── 📁 06-PHOI-HOP-DOI-TAC/             ← Phối hợp bên ngoài
│   ├── 📁 thiet-ke/
│   ├── 📁 nha-thau/
│   ├── 📁 nha-cung-cap/
│   └── 📁 co-quan-chuc-nang/
│
├── 📁 07-PHOI-HOP-NOI-BO/              ← Phối hợp phòng ban nội bộ
│   ├── phoi-hop-ke-toan.md
│   ├── phoi-hop-HR.md
│   ├── phoi-hop-marketing.md
│   ├── bao-cao-ban-giam-doc.md
│   └── escalation-noi-bo.md
│
├── 📁 08-BIEU-MAU-TEMPLATE/            ← Biểu mẫu chuẩn
│   ├── README.md
│   └── (các file mẫu)
│
└── 📁 09-PHU-LUC/                      ← Phụ lục & Tham khảo
    ├── FAQ.md
    ├── cam-ket-chat-luong.md
    ├── ticket-scorecard-escalation.md
    └── changelog.md
```

---

## 📊 Các Gói Dịch Vụ TLXN

| Gói              | Tên đầy đủ           | Đặc điểm                                       | Phạm vi        |
| ----------------- | ------------------------- | -------------------------------------------------- | --------------- |
| **QTDA**    | Quản Trị Dự Án        | Đại diện CĐT quản lý toàn bộ công trình  | TP.HCM (≤20km) |
| **TLXN**    | Trợ Lý Xây Nhà        | Hỗ trợ quản lý và nghiệm thu bán thời gian | TP.HCM (≤20km) |
| **TLXN TX** | Trợ Lý Xây Nhà Từ Xa | Hỗ trợ qua ảnh/video/online                     | Ngoại tỉnh    |

---

## 🔧 Công Cụ Sử Dụng

| Công cụ           | Mục đích                                       | Lưu ý                                                                            |
| ------------------- | ------------------------------------------------- | ---------------------------------------------------------------------------------- |
| **Larksuite** | Lưu trữ dữ liệu, Ticket, Scorecard, báo cáo | Kênh chính thức                                                                 |
| **Zalo**      | Giao tiếp nhanh với KH, đối tác, nội bộ    | Chỉ trao đổi nhanh, quyết định quan trọng phải xác nhận trên Lark/email |
| **HBSS**      | Hệ thống quản lý công trình                 | Phần mềm nội bộ NCM                                                            |
| **GitHub**    | Lưu trữ SOP (tài liệu này)                   | Cho nhân viên tra cứu                                                           |

---

## 📅 Tiến Độ Xây Dựng SOP

| Phase    | Nội dung                           | Trạng thái        |
| -------- | ----------------------------------- | ------------------- |
| Phase 1  | Tổng quan, Flow, RACI, Stakeholder | ✅ Hoàn thành     |
| Phase 2  | SOP Phối hợp Sale ↔ QLDA         | ✅ Hoàn thành     |
| Phase 3  | SOP Account                         | 🔲 Chưa bắt đầu |
| Phase 4  | SOP PM                              | 🔲 Chưa bắt đầu |
| Phase 5  | SOP AA                              | 🔲 Chưa bắt đầu |
| Phase 6  | SOP CA + Checklist                  | 🔲 Chưa bắt đầu |
| Phase 7  | Phối hợp Đối tác               | 🔲 Chưa bắt đầu |
| Phase 8  | Phối hợp Nội bộ                 | 🔲 Chưa bắt đầu |
| Phase 9  | Biểu mẫu + Phụ lục              | 🔲 Chưa bắt đầu |
| Phase 10 | Review & Hoàn thiện               | 🔲 Chưa bắt đầu |

---

## 📝 Changelog

| Ngày      | Phiên bản | Nội dung thay đổi                           |
| ---------- | ----------- | ---------------------------------------------- |
| 2026-03-27 | v1.0.0      | Khởi tạo cấu trúc SOP, Phase 1: Tổng quan |
| 2026-03-27 | v1.1.0      | Phase 2: SOP Phối hợp Sale ↔ QLDA (4 SOP)   |

---

*Maintained by Bộ phận QLDA — Nhà Của Mình AC*
