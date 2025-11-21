project:
  name: "Flowix – GateChain AI"
  subtitle: "Next-Generation Blockchain-Based Secure Access & Intelligent Visitor Management System"
  description: >
    Flowix ekibi tarafından geliştirilen GateChain AI, modern yaşam alanlarında giriş-çıkış
    güvenliğini yeniden tanımlayan, yüksek doğruluklu ve değiştirilemez bir blokzincir tabanlı
    akıllı erişim yönetimi çözümüdür. Sistem; kuryeler, misafirler, hizmet sağlayıcılar,
    site sakinleri ve kampüs personeli gibi tüm kullanıcı gruplarının giriş süreçlerini
    AI analitiği, zaman kısıtlı dinamik QR kodlar ve akıllı sözleşmelerle tamamen güvenli hale getirir.
    Flowix’in ürettiği bu çözüm, Emlak Konut gibi geniş ölçekli akıllı yaşam projelerinde 
    sahada uygulanabilecek yeni nesil bir güvenlik standardı sağlar.

features:
  blockchain_auth:
    title: "Blockchain Tabanlı Doğrulama Katmanı"
    points:
      - "Giriş yetkileri zincir üzerinde tutulur."
      - "Her işlem hash’lenerek değiştirilemez hale gelir."
      - "Manipülasyon ve sahtecilik imkansızlaştırılır."
      - "Merkezi veri tabanı gereksinimini ortadan kaldırır."

  dynamic_qr:
    title: "Dinamik & Zaman Sınırlı QR Kodlar"
    points:
      - "Kullanıcı tarafından oluşturulan tek kullanımlık giriş izinleri."
      - "Misafir davet sistemi."
      - "Kuryeler için canlı doğrulama."
      - "Süre bitişinde otomatik erişim iptali."

  ai_security:
    title: "Yapay Zeka Destekli Güvenlik Analitiği"
    points:
      - "Şüpheli giriş denemesi tespiti."
      - "Anomali farkındalığı (farklı saat, farklı kapı, tekrar deneme)."
      - "Yoğunluk tahmini."
      - "Risk puanlama modelleri."

  iot_integration:
    title: "IoT ile Tam Entegrasyon"
    points:
      - "Akıllı kapı sistemleri."
      - "Plaka tanıma kameraları."
      - "Kart/NFC sistemleri."
      - "Sensör ağı ve BMS entegrasyonu."

  admin_panel:
    title: "Yönetici Paneli (Web Dashboard)"
    points:
      - "Gerçek zamanlı giriş hareketi takibi."
      - "Filtreleme, log izleme ve izin yönetimi."
      - "KPI / SLA analitiği."
      - "Acil durum yönetimi ve bildirim sistemi."

technologies:
  frontend: "React / Next.js"
  backend: "Node.js / Express.js"
  blockchain: "Solidity, Ethereum / Polygon / Hyperledger"
  ai_services: "Python tabanlı anomali tespit motoru"
  qr_processing: "OpenCV"
  database: "PostgreSQL / Supabase"
  devops: "Docker"

architecture:
  flow: |
    Kullanıcı → Mobil Uygulama → QR Kod Üretici
                    ↓
            Blockchain Smart Contract
                    ↓
           Giriş Noktası Doğrulama Sistemi
                    ↓
           Flowix Yönetici Paneli (AI)

use_cases:
  - "Akıllı siteler ve rezidanslar"
  - "Teknokent ve Ar-Ge kampüsleri"
  - "Üniversite yerleşkeleri"
  - "Ofis kompleksleri"
  - "Lojistik merkezleri"
  - "Güvenlik hassasiyeti yüksek alanlar"

installation:
  commands: |
    git clone https://github.com/flowix-team/gatechain-ai.git
    cd gatechain-ai
    npm install
    npm run dev

contribution:
  note: >
    Flowix ekibi açık inovasyonu destekler. Pull request'ler, entegrasyon önerileri
    ve yeni özellik taleplerine açığız. Katkılarınızı memnuniyetle karşılıyoruz.

license: "MIT License"

team:
  - name: "Yasin Karaca"
    role: "Lead Developer"
  - name: "Flowix Team"
    role: "AI, Blockchain & Smart Infrastructure R&D"
