deal-platform/
├── public/
│   └── logo.png              # ไฟล์โลโก้ที่คุณแนบมา
├── src/
│   ├── assets/
│   │   └── global.css        # ตั้งค่าโทนสีตาม Document
│   ├── components/
│   │   ├── Navigation.jsx    # แถบเมนูด้านล่างหรือด้านบน
│   │   ├── SwipeCard.jsx     # คอมโพเนนต์สำหรับปัดขวา/ซ้าย
│   │   ├── ChatBubble.jsx    # คอมโพเนนต์แชท
│   │   └── AuctionItem.jsx   # คอมโพเนนต์การ์ดประมูล
│   ├── pages/
│   │   ├── Home.jsx          # หน้าหลัก (Tinder-like swipe)
│   │   ├── ChatList.jsx      # หน้าแชทและ Tracking
│   │   ├── Profile.jsx       # หน้าโปรไฟล์และประวัติการแลกของ
│   │   ├── Feed.jsx          # หน้าคอมมูนิตี้สำหรับค้นหา/โพสต์
│   │   └── Auction.jsx       # หน้าประมูลสินค้า
│   ├── App.jsx               # จัดการ Routing ของหน้าต่างๆ
│   └── main.jsx              # Entry point ของ React
├── package.json
└── tailwind.config.js
