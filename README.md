# Thai Voice Navigation for ETS2/ATS
[![Latest Release](https://img.shields.io/github/v/release/lazywasabi/ets2-thai-navigation?label=Latest%20Version&logo=github)](https://github.com/lazywasabi/ets2-thai-navigation/releases)
[![GitHub Downloads](https://img.shields.io/github/downloads/lazywasabi/ets2-thai-navigation/total?label=Downloads&logo=github)](https://github.com/lazywasabi/ets2-thai-navigation/releases)
[![Steam Subscriptions (ETS2)](https://img.shields.io/steam/subscriptions/1764313195?label=Steam%20Subscriptions%20%28ETS2%29&logo=steam)](https://steamcommunity.com/sharedfiles/filedetails/?id=1764313195)
[![Steam Subscriptions (ATS)](https://img.shields.io/steam/subscriptions/1900877329?label=Steam%20Subscriptions%20%28ATS%29&logo=steam)](https://steamcommunity.com/sharedfiles/filedetails/?id=1900877329)

ม็อดเสียงนำทางภาษาไทยสำหรับเกม Euro Truck Simulator 2 และ American Truck Simulator

- 🚚 รองรับเกม Euro Truck Simulator 2 และ American Truck Simulator
- 🔊 รองรับเอนจินเสียง FMOD®
- 🗣 3 เสียงนำทาง
  - Google TTS - เสียงที่ใช้ใน Google Maps
  - Microsoft TTS
  - Yuki - พากย์เสียงโดย [Yuki จาก Alone Studio](https://www.youtube.com/channel/UCp9esxbHaanP3hBLgfO96pQ) ตัดต่อโดย [hiyamikan](https://www.instagram.com/hiyamikan/)
- ✅ ไฟล์เสียงครบทุกคำสั่ง
- ⚠️ รองรับการเตือนจำกัดความเร็วทั้งเสียงพูดและสัญญาณเตือน
- 👥 รองรับโหมดเล่นหลายคน (Convoy)

## ดาวน์โหลด

เวอร์ชันม็อด 5.0.1 อัปเดตล่าสุด 9 ต.ค. 2566  
รองรับเกมเวอร์ชัน 1.43 - 1.48

**ดาวน์โหลดผ่าน Steam Workshop:**
- [Euro Truck Simulator 2](https://steamcommunity.com/sharedfiles/filedetails/?id=1764313195)
- [American Truck Simulator](https://steamcommunity.com/sharedfiles/filedetails/?id=1900877329)

**ดาวน์โหลดไฟล์ม็อดโดยตรง:** (ทั้ง 2 เกมใช้ไฟล์ม็อดเดียวกัน)
- [thai-navigation-5.0.1.scs](https://github.com/lazywasabi/ets2-thai-navigation/releases/download/v5.0.1/thai-navigation.scs)

## วิธีใช้งาน

- เปิดใช้งานม็อด โดยวางไว้ตำแหน่งใดก็ได้ในรายการม็อด
- เข้าเมนูตั้งค่า Options > Audio
- เปิดใช้งาน Voice Navigation
- ในตัวเลือก Language and voice เลือก "Thai - Google TTS" หรือ "Thai - Microsoft TTS" หรือ "Thai - Yuki"
- เลือกตัวเลือกเสียงเตือนจำกัดความเร็ว Speed warning ระหว่าง "Sound" (สัญญาณเตือน) หรือ "Voice" (เสียงพูด)
- หากเสียงนำทางเบาหรือดังเกินไป ปรับระดับเสียงได้ที่เมนู Voice navigation volume ด้านบน
- สำหรับโหมดเล่นหลายคน (Convoy) สามารถใช้ม็อดนี้เล่นได้เลย โดยผู้เล่นอื่นไม่จำเป็นต้องดาวน์โหลดม็อดนี้

## เสียงพูดและคำแปล

| **ชื่อไฟล์**         | **ต้นฉบับ**                            | **คำแปล**                           |
| -------------------- | -------------------------------------- | ----------------------------------- |
| and_then_exit_left   | and then exit left                     | จากนั้นใช้ทางออกด้านซ้าย            |
| and_then_exit_right  | and then exit right                    | จากนั้นใช้ทางออกด้านขวา             |
| and_then_go_straight | and then continue straight on          | จากนั้นวิ่งตรงต่อไป                 |
| and_then_keep_left   | and then keep left                     | จากนั้นชิดซ้าย                      |
| and_then_keep_right  | and then keep right                    | จากนั้นชิดขวา                       |
| and_then_turn_left   | and then turn left                     | จากนั้นเลี้ยวซ้าย                    |
| and_then_turn_right  | and then turn right                    | จากนั้นเลี้ยวขวา                   |
| compound_exit_left   | Exit left                              | ใช้ทางออกด้านซ้าย                   |
| compound_exit_right  | Exit right                             | ใช้ทางออกด้านขวา                    |
| compound_go_straight | Go straight on                         | วิ่งตรงต่อไป                        |
| compound_keep_left   | Keep left                              | ชิดซ้าย                             |
| compound_keep_right  | Keep right                             | ชิดขวา                              |
| compound_turn_left   | Turn left                              | เลี้ยวซ้าย                          |
| compound_turn_right  | Turn right                             | เลี้ยวขวา                           |
| exit_left            | Exit left                              | ใช้ทางออกด้านซ้าย                   |
| exit_now             | Exit now                               | ออกจากวงเวียน                       |
| exit_right           | Exit right                             | ใช้ทางออกด้านขวา                    |
| finish               | Here we are                            | ที่นี่คือจุดหมายของคุณ              |
| go_straight          | Go straight on                         | วิ่งตรงต่อไป                        |
| keep_left            | Keep left                              | ชิดซ้าย                             |
| keep_right           | Keep right                             | ชิดขวา                              |
| prepare_exit_left    | Get ready to exit left                 | เตรียมใช้ทางออกด้านซ้าย             |
| prepare_exit_right   | Get ready to exit right                | เตรียมใช้ทางออกด้านขวา              |
| prepare_turn_left    | Get ready to turn left                 | เตรียมเลี้ยวซ้าย                     |
| prepare_turn_right   | Get ready to turn right                | เตรียมเลี้ยวขวา                    |
| recomputing          | Recomputing                            | กำลังค้นหาเส้นทางใหม่               |
| roundabout_1         | At the roundabout take the first exit  | เมื่อถึงวงเวียนใช้ทางออกที่หนึ่ง    |
| roundabout_2         | At the roundabout take the second exit | เมื่อถึงวงเวียนใช้ทางออกที่สอง      |
| roundabout_3         | At the roundabout take the third exit  | เมื่อถึงวงเวียนใช้ทางออกที่สาม      |
| roundabout_4         | At the roundabout take the fourth exit | เมื่อถึงวงเวียนใช้ทางออกที่สี่      |
| roundabout_5         | At the roundabout take the fifth exit  | เมื่อถึงวงเวียนใช้ทางออกที่ห้า      |
| roundabout_6         | At the roundabout take the sixth exit  | เมื่อถึงวงเวียนใช้ทางออกที่หก       |
| speed_signal         | –                                      | –                                   |
| speed_warning        | Caution, please mind the speed limit   | คุณใช้ความเร็วเกิน, กรุณาลดความเร็ว |
| start                | OK, here we go!                        | เริ่มต้นนำทาง                       |
| turn_left            | Turn left                              | เลี้ยวซ้าย                          |
| turn_right           | Turn right                             | เลี้ยวขวา                           |
| u_turn               | Make a u-turn                          | กลับรถ                              |

## ขอบคุณ

- [SCS Software](https://scssoft.com/)
- เทมเพลตม็อดจาก [Wombat Trucker](https://www.youtube.com/watch?v=ax-6sP_PVpU)
- เสียงพูดจาก [Google TTS](https://cloud.google.com/text-to-speech) และ [TTSMaker](https://ttsmaker.com/)
- เสียง Yuki พากย์เสียงโดย [Yuki จาก Alone Studio](https://www.youtube.com/channel/UCp9esxbHaanP3hBLgfO96pQ) และตัดต่อโดย [hiyamikan](https://www.instagram.com/hiyamikan/)
- [FMOD Studio](https://www.fmod.com/studio)
- เครื่องมือ[แปลงเสียง FMOD จาก Koen](https://forum.scssoft.com/viewtopic.php?f=201&t=282438)
- ข้อมูลจากกระทู้ [FMOD Discussion](https://forum.scssoft.com/viewtopic.php?f=178&t=281124)
