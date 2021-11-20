# Miniproject_Dropdown_menu
### การใช้ Dropdown เพื่อเรียกใช้ Function ในการสร้าง Waveform
> โดยผู้ใช้สามารถเลือกชนิดของสัญญาณที่มีคาบ จาก Menu Dropdown ซึ่งการทำงานโดยรวมของฟังก์ชั่นจากโค้ดแล้วคือเมื่อ เปิดเครื่อง เลือกกราฟสัญญาณ แล้วให้ตั้งค่า พารามิเตอร์( Amplitude , Frquency ) หลังจากนั้นปรับค่า Time/div , Offset เพื่อเลื่อนกราฟให้เห็นชัดมากยิ่งขึ้น เราจะสามารถจำลอง Waveform ต่างๆซึ่งการปรับค่าในส่วนต่างๆสามารถทำได้แบบ Real-Time

![image](https://user-images.githubusercontent.com/87509688/142722815-c9a6c339-2e19-49a6-ab64-09cfc31392ff.png)

> ผู้ใช้สามารถกดปุ่ม clear เพื่อล้างค่าพารามิเตอร์และกราฟทั้งหมดได้

![image](https://user-images.githubusercontent.com/20890109/142723348-59f32214-ed48-4b98-b083-52038696df58.png)


                    
โดยการที่จะสร้างสมการ X(t) ซึ่งจะสามารถหาสมการได้จากการ นำความรู้เรื่อง Fourier Series มาใช้เพื่อหาผลลัพธ์ของสมการ
> ซึ่งผลลัพธ์จากการคำนวนได้ดังนี้

> ### Sine Wave 

![image](https://user-images.githubusercontent.com/87509688/142722805-31e417de-f455-4076-bc87-b18d74d47d1e.png)
![image](https://user-images.githubusercontent.com/87509688/142723130-4e66d9fc-8d7b-475e-bf3b-d7d59806023e.png)

> ### Square Wave 

![image](https://user-images.githubusercontent.com/87509688/142722634-1ed24a6e-5653-413a-86df-800b0bb64045.png)
![image](https://user-images.githubusercontent.com/87509688/142722714-e88b7f38-a460-44a7-9b0d-4ba32d51087c.png)
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
> https://github.com/Ekalak01/Miniproject_Dropdown_menu.git และสามารถดูคลิปขั้นตอนและวิธีการใช้งานการอธิบายอย่างละเอียดได้ที่ https://youtu.be/MESQOOBAH0g

