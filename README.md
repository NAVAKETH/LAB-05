#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้
  

![](https://github.com/NAVAKETH/LAB-05/blob/master/6.1.PNG?raw=true)

 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้

  ![](https://github.com/NAVAKETH/LAB-05/blob/master/6.2.PNG?raw=true)

###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร
<hr>
<hr>
<hr>มีการดึงข้อมูลแบบอาร์เรย์มาใช้
<hr>
<hr>
###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย
<hr>
<hr>
<hr>ใช้ได้เนื่องจากค่าของอาร์เรย์นั้นสามารถกระทำแบบการเรียกผ่านแอสเดรสของค่านั้นๆทำให้เราไม่จำเป็นต้องดึงค่าแบบลำดับแต่สามารถดึงค่าแบบเรียกใช้แบบกระโดดได้หมดตราบเท่าที่ขนาดของอาร์เรยนั้นถูกสร้างไว้
<hr>
<hr>
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้
<hr>
<hr>
<hr>
![](https://github.com/NAVAKETH/LAB-05/blob/master/6.4.PNG?raw=true)
<hr>
<hr>

3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้
<hr>
<hr>
<hr>
![](https://github.com/NAVAKETH/LAB-05/blob/master/6.5.PNG?raw=true)
<hr>
<hr>

###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร
<hr>
<hr>
<hr>
<hr>
มีการกำหนดความกว้างตามแกนxโดยตามค่าที่กำหนดหลัง,
<hr>


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้
<hr>
<hr>
<hr>
  ![](https://github.com/NAVAKETH/LAB-05/blob/master/6.7.PNG)
<hr>
<hr>

5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
  ![](https://github.com/NAVAKETH/LAB-05/blob/master/6.6.PNG)
6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้
  
  ![](https://github.com/NAVAKETH/LAB-05/blob/master/6.8.PNG)

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
    #### ตอบ.Hello there. I said Hello! Hello???
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
    #### ตอบ.3 1 2
3.    Console.WriteLine("Hello " + "World");
    #### ตอบ.Hello World
4.    Console.WriteLine("Here comes a slash \\");
    #### ตอบ.Here comes a slash \
5.    Console.WriteLine("|{0, 10}|", 999);
    #### ตอบ.          999          |       
6.    Console.WriteLine("|{0,-10}|", 000);
    #### ตอบ.0
7.    Console.WriteLine("The value: {0}.", 500);
    #### ตอบ.The value: 500
8.    Console.WriteLine("The value: {0:C}.", 500);
    #### ตอบ.The value: ฿500.00.
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
    #### ตอบ.12.3457
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
    #### ตอบ.฿12.35
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
    #### ตอบ.1.235E+001
12.   Console.WriteLine("{0,-10:x}", 65535);
    #### ตอบ.ffff
13.   Console.WriteLine("{0,-10:X}", 65535);
    #### ตอบ.FFFF
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
    #### ตอบ.
Value   Squared Cubed
1       1       1
2       4       8
3       9       27
4       16      64
5       25      125
6       36      216
7       49      343
8       64      512
9       81      729
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
    #### ตอบ.1234.568.
```
