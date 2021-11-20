# Miniproject_Dropdown_menu
### การใช้ Dropdown เพื่อเรียกใช้ Function ในการสร้าง Waveform
> โดยผู้ใช้สามารถเลือกชนิดของสัญญาณที่มีคาบ จาก Menu Dropdown ซึ่งการทำงานโดยรวมของฟังก์ชั่นจากโค้ดแล้วคือเมื่อ เปิดเครื่อง เลือกกราฟสัญญาณ แล้วให้ตั้งค่า พารามิเตอร์( Amplitude , Frquency ) 
> หลังจากนั้นปรับค่า Time/div , Offset เพื่อเลื่อนกราฟให้เห็นชัดมากยิ่งขึ้น เราจะสามารถจำลอง Waveform ต่างๆซึ่งการปรับค่าในส่วนต่างๆสามารถทำได้แบบ Real-Time

![image](https://user-images.githubusercontent.com/87509688/142722815-c9a6c339-2e19-49a6-ab64-09cfc31392ff.png)

> ใช้สามารถปรับค่า Time/Div และเลือกหน่วยได้จาก Menu Dropdown โดยจะมี s, ms และ us โดยใช้เพื่อเลื่อนตำแหน่งของ กราฟฝั่ง Time/div เพื่อให้เห็นรูปกราฟชัดมากขึ้น

![image](https://user-images.githubusercontent.com/20890109/142723856-78e01166-2f1b-4e54-8c35-27b322594455.png)

> ผู้ใช้สามารถปรับค่า Offset ได้

![image](https://user-images.githubusercontent.com/20890109/142723888-7e077783-f1de-46bd-b246-5d01d505baaa.png)

> ผู้ใช้สามารถกดปุ่ม Clear เพื่อล้างค่าพารามิเตอร์และกราฟทั้งหมดได้

![image](https://user-images.githubusercontent.com/20890109/142723597-d02912ad-9f1d-44da-85e4-7d5c79ea4168.png)


                    
โดยการที่จะสร้างสมการ X(t) ซึ่งจะสามารถหาสมการได้จากการ นำความรู้เรื่อง Fourier Series มาใช้เพื่อหาผลลัพธ์ของสมการ
เมื่อผู้ใช้ตั้งค่าในพารามิเตอร์เรียบร้อยแล้วสามารถที่จะ Plot รูป Waveform ต่างๆได้ตามที่ผู้ใช้ปรับเปลี่ยน

> ซึ่งผลลัพธ์จากการคำนวนได้ดังนี้

> ### Sine Wave 

![image](https://user-images.githubusercontent.com/87509688/142724034-03b2b845-06f2-4784-830c-c1559a821227.png)
![image](https://user-images.githubusercontent.com/87509688/142723130-4e66d9fc-8d7b-475e-bf3b-d7d59806023e.png)

> ### Square Wave 

![image](https://user-images.githubusercontent.com/87509688/142724061-20ee9df7-4242-46bb-ba46-ff2cde2cc6a3.png)
![image](https://user-images.githubusercontent.com/87509688/142724067-6ea8fe67-c537-43ad-b7e5-caeff48bad9d.png)
![image](https://user-images.githubusercontent.com/87509688/142723101-d6e6d390-d556-4382-889b-2f965bb8ffe3.png)


> ### Traingular Wave 

![image](https://user-images.githubusercontent.com/87509688/142722873-7a1c9bb8-e440-487b-9aa3-a17832865506.png)
![image](https://user-images.githubusercontent.com/87509688/142722853-79b1a16d-14b7-4c2f-b0c7-01ddd20bf207.png)
![image](https://user-images.githubusercontent.com/87509688/142723110-35e31ac2-5bb6-4105-bfd9-4963389dcf91.png)


> ### Sawtooth Wave 

![image](https://user-images.githubusercontent.com/87509688/142722770-6f5c3fb9-3744-48cb-8927-80637c379a41.png)
![image](https://user-images.githubusercontent.com/87509688/142722784-82a2b41e-bd67-4217-a4da-5f5a7f3e4a0a.png)
![image](https://user-images.githubusercontent.com/87509688/142723115-6a31d6e0-8ddd-4a6e-b275-954a6a2a84de.png)

> #### จากการกล่าวถึงโปรเจคข้างต้น ซึ่งผู้อ่านสามารถ โหลดไฟล์ GUI MATLAB ได้ที่ 
> https://github.com/Ekalak01/Miniproject_Dropdown_menu.git 
> 
> และสามารถดูคลิปขั้นตอนและวิธีการใช้งานการอธิบายอย่างละเอียดได้ที่ 
> 
> https://youtu.be/MESQOOBAH0g

