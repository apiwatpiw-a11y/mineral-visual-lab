# วิชวลแล็บทดสอบสมบัติของแร่ (Mineral Visual Lab)

**เปิดใช้งาน:** https://apiwatpiw-a11y.github.io/mineral-visual-lab/

ห้องปฏิบัติการเสมือนสำหรับนักเรียนมัธยมศึกษาตอนปลาย ใช้ฝึกทดสอบสมบัติทางกายภาพของแร่ 16 ชนิด แล้วใช้หลักฐานที่ได้ระบุชนิดของแร่ปริศนา

- ขูดก้อนแร่ด้วยเล็บมือ เหรียญทองแดง ตะปูเหล็ก และแผ่นกระจก เพื่ออนุมานความแข็ง (hardness) ตามมาตราโมส์
- ตรวจสีผงละเอียด (streak) ด้วยแผ่นกระเบื้องขูดสี ตรวจการดูดติดแม่เหล็ก และการทำปฏิกิริยากับกรดไฮโดรคลอริกเจือจาง
- ส่องผิวแร่ด้วยแว่นขยาย และหมุนดูโมเดล 3 มิติที่สแกนจากก้อนแร่จริง
- สแกนดูเส้นแลตทิซ เซลล์หน่วย ตำแหน่งอะตอม และระบบผลึก (crystal system)
- ภารกิจแร่ปริศนา พร้อมระบบลงทะเบียน เก็บคะแนน และจัดอันดับเหรียญทอง เงิน ทองแดง

## วิธีใช้ในชั้นเรียน

1. ให้นักเรียนเปิดลิงก์ด้านบนหรือสแกน QR code ได้ทั้งคอมพิวเตอร์ แท็บเล็ต และโทรศัพท์ ไม่ต้องมีบัญชีและไม่ต้องติดตั้งโปรแกรม
2. แล็บทั้งหมดอยู่ในไฟล์ `index.html` ไฟล์เดียว (ประมาณ 10 MB) การเปิดครั้งแรกอาจใช้เวลาโหลดสักครู่ หรือดาวน์โหลดไฟล์ไปเปิดในเครื่องโดยไม่ต้องใช้อินเทอร์เน็ตก็ได้
3. คะแนนเก็บไว้ในเบราว์เซอร์ของเครื่องที่เปิดเท่านั้น จบรอบแล้วให้นักเรียนคัดลอกรหัสผลคะแนน (ขึ้นต้นด้วย `ML1.`) ส่งครู
4. ครูเปิดแล็บในเครื่องของครู ไปที่ **เครื่องมือครู** ในส่วนตารางอันดับ วางรหัสของนักเรียนบรรทัดละหนึ่งรหัส แล้วกด **นำเข้ารหัสผลคะแนน** เพื่อรวมเป็นตารางอันดับของห้อง และดาวน์โหลดตารางคะแนนเป็นไฟล์ CSV ได้

## เครดิตโมเดล 3 มิติ

โมเดลสแกนจาก Sketchfab ทุกชิ้นถูกปรับลดจำนวนเหลี่ยมและบีบอัดภาพพื้นผิวเพื่อลดขนาดไฟล์ ส่วนเพชรเป็นแบบจำลองผลึกที่สร้างด้วยโค้ด

| แร่ | โมเดล | ผู้สร้าง | สัญญาอนุญาต |
|---|---|---|---|
| ทัลก์ | [Talc / RU Geology / by Grace Psenicska](https://sketchfab.com/3d-models/talc-ru-geology-by-grace-psenicska-4ff637a3897d4cc09879b128221a21bb) | Dr. Parvinder Sethi | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| แคลไซต์ | [Calcite](https://sketchfab.com/3d-models/calcite-af17af4019294091a38f2fc990fb2a79) | Frank McMains | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| แกรไฟต์ | [Graphite Mineral](https://sketchfab.com/3d-models/graphite-mineral-1461578612f648ada3f0db291744b245) | ESUEarthSci | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| กาลีนา | [Galena](https://sketchfab.com/3d-models/galena-bdb542796b3d498494c62afeec98481e) | EDUROCK – Educational Virtual Rock Collection | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| เฮไลต์ | [Halite](https://sketchfab.com/3d-models/halite-82ab33239f8549c3ab353f7335d77e4d) | Dr. Parvinder Sethi | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| ยิปซัม | [Gypsum](https://sketchfab.com/3d-models/gypsum-de785119fe014b5e998a17e0fdcf6850) | EDUROCK – Educational Virtual Rock Collection | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| แมกนีไทต์ | [Magnetite](https://sketchfab.com/3d-models/magnetite-b151bbb5f9e84d8388024ed6117dfa81) | EDUROCK – Educational Virtual Rock Collection | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| อะพาไทต์ | [Apatite](https://sketchfab.com/3d-models/apatite-1b6fb9670a754d00ad68e65e833083b2) | EDUROCK – Educational Virtual Rock Collection | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| ฟลูออไรต์ | [Mineral: Fluorite](https://sketchfab.com/3d-models/mineral-fluorite-5ed87d4487be495aac0a86632eb3880c) | Digital Atlas of Ancient Life | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |
| ฮีมาไทต์ | [Hematite](https://sketchfab.com/3d-models/hematite-f87123b191804e4bac73ce34a42e073e) | EDUROCK – Educational Virtual Rock Collection | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| ออร์โทเคลส | [Orthoclase Feldspar](https://sketchfab.com/3d-models/orthoclase-feldspar-a8ab6e5cc9cd4378aaef339e4e5684a6) | Digital Atlas of Ancient Life | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |
| คอรันดัม | [Corundum](https://sketchfab.com/3d-models/corundum-5c09154cb6f849caa880f22349e3724e) | Earth Sciences, University of Newcastle | [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (ห้ามใช้เพื่อการค้า) |
| ไพไรต์ | [Pyrite](https://sketchfab.com/3d-models/pyrite-4084c7078cff40cf94890bbe001f0d47) | Tavernier Amaury | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) (ห้ามใช้เพื่อการค้า และโมเดลที่ดัดแปลงแล้วเผยแพร่ภายใต้สัญญาอนุญาตเดียวกัน) |
| ควอตซ์ | [Orange Quartz mineral](https://sketchfab.com/3d-models/orange-quartz-mineral-64b8db17dcbc48558280674c3727ea79) | matousekfoto | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| โทแพซ | [Topaz](https://sketchfab.com/3d-models/topaz-a30c9073f8ed4f0a8ab653dc84a672e5) | EDUROCK – Educational Virtual Rock Collection | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

เนื่องจากโมเดลคอรันดัมและไพไรต์ใช้สัญญาอนุญาตแบบไม่ใช้เพื่อการค้า (NC) แล็บนี้จึงเผยแพร่เพื่อการศึกษาเท่านั้น

## ซอฟต์แวร์และฟอนต์ที่รวมอยู่ในไฟล์

- [three.js](https://threejs.org/) r150 — MIT License, Copyright 2010–2023 Three.js Authors
- ฟอนต์ [Bai Jamjuree](https://fonts.google.com/specimen/Bai+Jamjuree) ออกแบบโดย Cadson Demak — SIL Open Font License 1.1

## แหล่งข้อมูลที่ใช้ตรวจสอบข้อมูลแร่

- Handbook of Mineralogy — https://www.handbookofmineralogy.org/
- Mindat.org — https://www.mindat.org/
- American Mineralogist Crystal Structure Database (AMCSD) — https://rruff.geo.arizona.edu/AMS/amcsd.php
- Crystallography Open Database (COD) — https://www.crystallography.net/cod/
