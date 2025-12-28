.avatar {
  border-radius: 50%;
  border: 2px solid white;
}

.one,
.selector,
.per-line {
  // ...
}

Incident Timeline Builder

TR

Bu araç, bir siber güvenlik vakası sırasında gerçekleşen karmaşık olay akışlarını standart bir kronolojik yapıda birleştirerek analiz süresini kısaltmaktadır.

Aracın Temel Teknik Yetenekleri:

Dinamik Kronoloji: Farklı log kaynaklarından gelen verileri otomatik olarak zaman sırasına dizer ve manuel düzenleme ihtiyacını ortadan kaldırır.

Severity-Based Visualizer: Olaylar, önem derecelerine göre (Kritik, Yüksek, Orta) renk kodlarıyla işaretlenerek öncelikli risklerin anlık olarak tespit edilmesini sağlar.

Veri Bütünlüğü: Tarayıcı tabanlı yerel depolama (LocalStorage) kullanarak veri kaybını önler; oturum kapansa dahi mevcut çalışma korunur.

Yapılandırılmış Çıktı Yönetimi: Analiz sonuçları, resmi raporlar için TXT veya veri işleme sistemleri için JSON formatında hızlıca dışa aktarılabilir.

EN

This tool reduces analysis time by consolidating complex event flows occurring during a cybersecurity incident into a standard chronological structure.

Key Technical Capabilities of the Tool:

Dynamic Chronology: Automatically sorts data from different log sources in chronological order, eliminating the need for manual editing.

Severity-Based Visualizer: Events are color-coded according to their severity (Critical, High, Medium), enabling instant identification of priority risks.

Data Integrity: Prevents data loss by using browser-based local storage (LocalStorage); current work is preserved even if the session closes.

Structured Output Management: Analysis results can be quickly exported in TXT format for official reports or in JSON format for data processing systems.    
