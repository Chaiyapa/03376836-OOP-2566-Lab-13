### บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/Chaiyapa/03376836-OOP-2566-Lab-13/assets/144195729/9f695dbd-e7fa-4b6f-8f6c-1e33ea987a7b)
Build ได้ เพราะ ISpeakable.Speak() ถูกประกาศลง abstract class และการสืบทอด Animal.Speak() ถูกเพิ่มไปยัง Bird, Dog, Fish
### บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/Chaiyapa/03376836-OOP-2566-Lab-13/assets/144195729/55accf6f-a180-42bd-aeb9-04ed85f08264)

Run ได้ เพราะ ทุกคลาสที่สืบทอดมาจาก animal มี Interface Speak() ที่เพิ่มเข้ามาแล้ว และ ถูก override
### อธิบายสิ่งที่พบในการทดลอง
โปรแกรมจะแสดงผล

Dog move by running on the ground

Dog speak "Bok Bok"

Bird move by flying in the air

Bird speak "Jib Jib"

Fish move by swimming in the water

Fish can not speak
