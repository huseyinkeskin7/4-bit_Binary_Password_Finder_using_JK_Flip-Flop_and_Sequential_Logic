# 4-bit_Binary_Password_Finder_using_JK_Flip-Flop_and_Sequential_Logic
# Türkçe
Bu proje, Simulink kullanılarak tasarlanmış 4-bit binary şifre bulucu sistemidir. Tasarımda JK flip-flop, XNOR kapısı ve ardışıl (sequential) mantık devreleri kullanılmıştır.
Devre, 4-bit senkron sayaç ile tüm olası kombinasyonları (0000–1111) sırasıyla deneyerek, kullanıcı tarafından girilen binary şifreyi bulmaya çalışır. Şifre bulunduğunda sistem durur.
💡 Özellikler:
    🔁 JK Flip-Flop’larla 4-bit yukarı sayıcı (synchronous up counter)
    🔒 XNOR kapıları ile kullanıcı girişi karşılaştırması
    🛑 Eşleşme anında sistemin döngüden çıkması
    ✅ Durum diyagramı, tablo, Karnaugh haritaları ve mantık denklemleri detaylıca çıkarılmıştır
    🛠️ Simulink devresi, çıkarılan denklemlere göre modellenmiştir

# English
This project demonstrates the design of a 4-bit binary password finder using JK flip-flops, XNOR gates, and sequential logic circuits, implemented in Simulink.
The system is designed to brute-force all possible 4-bit binary combinations (from 0000 to 1111) using a 4-bit synchronous counter until it finds a match with a predefined user input. Once a match is detected, the system stops the counter loop.
💡 Features:
    🔁 4-bit up counter using synchronous JK Flip-Flops
    🔒 XNOR gate logic for matching user input with current counter state
    🛑 Stop condition via NOT gate logic once password match is detected
    ✅ State Diagram, State Table, Karnaugh Maps, and Boolean Equations derived manually
    🛠️ Simulink implementation based on derived logic equations
