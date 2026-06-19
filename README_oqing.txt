==================================================
  CS 1.6 - O'RNATISH QO'LLANMASI (Avazbek)
==================================================

Ikkita fayl bor:
  1) autoexec.cfg  -> SIZNING shaxsiy sozlamalaringiz (crosshair, aim, grafika)
  2) server.cfg    -> SIZ HOST bo'lganda server sozlamalari (tezlik, sakrash, pul)


--------------------------------------------------
1-QADAM: Fayllarni qayerga tashlash
--------------------------------------------------
Ikkala faylni ham shu papkaga tashlang:

   ...\Steam\steamapps\common\Half-Life\cstrike\

   (Eski versiya bo'lsa: ...\Counter-Strike 1.6\cstrike\)


--------------------------------------------------
2-QADAM: autoexec.cfg ishlayotganini tekshirish
--------------------------------------------------
- O'yinni oching.
- Konsolda yashil yozuv chiqsa - ishladi:
    "Avazbek config yuklandi!"
- Konsol chiqmasa: O'yin Sozlamalari -> Klaviatura ->
  Advanced -> "Enable developer console" ni belgilang.
  Konsol tugmasi: ~ (tilde)


--------------------------------------------------
3-QADAM: Do'st bilan o'ynash (IP orqali)
--------------------------------------------------
SIZ (host):
  1. Konsolni oching (~).
  2. Yozing:  exec server.cfg
  3. Yangi o'yin oching:  Create Server / Yangi o'yin
  4. O'z IP manzilingizni bilish uchun konsolda:  status
     (yoki internetda "my ip" deb qidiring - bu tashqi IP)

DO'STINGIZ:
  1. Konsolni oching (~).
  2. Yozing:  connect SIZNING_IP:27015
     Masalan:  connect 192.168.1.5:27015


--------------------------------------------------
ESLATMA
--------------------------------------------------
- Bir uydagi (bitta Wi-Fi) bo'lsangiz: ichki IP (192.168.x.x) ishlaydi.
- Internet orqali bo'lsa: router'da 27015 portini ochish (port forward)
  kerak bo'lishi mumkin.
- Hamma sozlama o'yinning rasmiy buyruqlari - ban yo'q,
  faqat o'z serveringizda ishlaydi.

Omad, bro! :)
