# helloworld ⛵

My first project on GitHub: a small Python program that prints **Hello World** followed by a sailboat drawn in ASCII art.

โปรเจกต์แรกบน GitHub: โปรแกรม Python เล็กๆ ที่พิมพ์คำว่า **Hello World** แล้วตามด้วยภาพเรือใบแบบ ASCII

## ตัวอย่างผลลัพธ์

```
Hello World

                      \   |   /
        |>          --    O    --
        |\            /   |   \
        | \                         v
        |  \                  v
        |   \
        |____\
   _____|_______
   \           /
~~~~\_________/~~~~~~~~~~~~~
  ~~    ~~~      ~~~   ~~
```

## วิธีรัน

ต้องมี Python 3 ติดตั้งอยู่ในเครื่อง

```bash
git clone https://github.com/achrtt/helloworld.git
cd helloworld
python hello.py
```

## ไฟล์ในโปรเจกต์

| ไฟล์ | รายละเอียด |
|------|-----------|
| `hello.py` | โปรแกรมหลัก พิมพ์ Hello World และภาพเรือใบ |
| `README.md` | ไฟล์อธิบายโปรเจกต์ (ไฟล์นี้) |

## เกร็ดเล็กๆ

ภาพเรือใบเก็บไว้ใน raw string (`r"""..."""`) เพื่อให้เครื่องหมาย `\` แสดงผลตรงตามที่วาด
ถ้าใช้ string ธรรมดา Python จะตีความ `\` ท้ายบรรทัดเป็นการต่อบรรทัด ทำให้ภาพเพี้ยน
