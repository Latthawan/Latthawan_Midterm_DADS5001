# Latthawan-Mini-Project_Midterm_DADS5001
# Topic : การวิเคราะห์ข้อมูลปริมาณน้ำฝนกับพื้นที่เสียงน้ำท่วมในประเทศไทย ปี 2022
  บทความนี้ จัดทำขึ้นเพื่อนำข้อมูลปริมาณน้ำฝนกับพื้นที่เสียงน้ำท่วม มาทำการวิเคราะห์ เพื่อดูเทรนของปริมาณน้ำฝนรายปี รายเดือน ตามภูมิภาค เเละจังหวัดที่มีพื้นที่เสี่ยง
เเละวิเคราะห์ต่อว่าในพื้นที่จังหวัดที่มีฝนตกปริมาณมากๆ จะมีความเสี่ยงสูงที่จะน้ำท่วมหรือไม่? 
หมายเหตุ:ปริมาณน้ำฝนหน่วยมิลลิเมตร

# Author
ลัทธวรรณ จันทรสุขา

รหัสนักศึกษา 6420422015

วิชา DADS5001 เครื่องมือและการเขียนโปรแกรมสําหรับการวิเคราะห์ข้อมูลและวิทยาการข้อมูล (Data Analytics and Data Science Tools and Programming)

# Dataset

แหล่งข้อมูลที่ใช้ในการทำ สามารถดาวน์โหลดได้จากทาง link หรือไฟล์ excel ด้านบนค่ะ
  1. https://data.go.th/dataset/spatial-rain 
  2. https://data.go.th/dataset/flood-area 
  3. https://data.go.th/dataset/proviceandregionthailand 

 
# Question & Answer
  1. สถิติแนวโน้มปริมาณน้ำฝนของปี 2018 – 2022 รายเดือน เป็นอย่างไร => จะพบว่า ปริมาณน้ำฝนจะมีมากในช่วงเดือนสิงหาคม ถึงกันยายน เเละจะไม่ค่อยมีฝนในช่วง เดือนมกราคม ถึงมีนาคม และเดือนตุลาคม ถึงธันวาคม
  2. สถิติแนวโน้มปริมาณน้ำฝนของปี 2018 – 2022 ตามภูมิภาค เป็นอย่างไร =>จะพบว่า ภาคตะวันออกเฉียงเหนือจะมีปริมาณน้ำฝนมากที่สุด ในปี 2022 ภาคเหนือ ภาคกลาง และภาคตะวันออกเฉียงเหนือ ปริมาณน้ำฝนจะสูงกว่า 4 ปีย้อนหลัง ส่วนภาคใต้ปริมาณน้ำฝนจะลดลง
  3. สถิติแนวโน้มปริมาณน้ำฝนของปี 2022 ตามภูมิภาค เป็นอย่างไร =>จะพบว่าภาคใต้ ภาคเหนือ และภาคกลางจะมีฝนตกอยู่ตลอดเริ่มตั้งเเต่ต้นปีจนถึงเดือนสิงหาคม ส่วนภาคตะวันออกเฉียงเหนือ จะเริ่มมีฝนในเดือนพฤษภาคม เป็นต้นมาเเละในเดือนสิงหาคม มีปริมาณน้ำฝนมากที่สุด
  3. สถิติแนวโน้มปริมาณน้ำฝนของปี 2022 เดือนสิงหาคม ภูมิภาคใดที่ปริมาณน้ำฝนมากที่สุด  => จะพบว่า ภูมิภาคที่มีปริมาณน้ำฝนมากที่สุด คือ ภาคตะวันออกเฉียงเหนือ
  4. 10 อันดับ จังหวัด ที่ปริมาณน้ำฝนมากที่สุด =>จังหวัดนครนายก จังหวัดบึงกาฬ จังหวัดปราจีนบุรี จังหวัดเชียงราย  จังหวัดอุบลราชธานี จังหวัดอำนาจเจริญ จังหวัดนครพนม จังหวัดหนองคาย จังหวัดมุกดาหาร จังหวัดยโสธร ตามลำดับ
  5. จังหวัดที่มีความเสี่ยงสูง ที่จะเกิดน้ำท่วม =>จะพบว่า จังหวัดที่มีจำนวนตำบล ที่มีความเสี่ยงสูงที่จะเกิดน้ำท่วมมากที่สุด คือ จังหวัดสุโขทัย
  6. พื้นที่จังหวัดที่มีฝนตกปริมาณมากๆ จะมีความเสี่ยงสูงที่จะน้ำท่วมหรือไม่ => จะพบว่า จังหวัดนครนายก ที่มีปริมาณน้ำฝนมากที่สุด ไม่ได้เป็นจังหวัดที่มีความเสี่ยงน้ำท่วมสูง เเต่ก็จะมีบางจังหวัดที่มีปริมาณน้ำฝนอยู่ใน 10 อันดับแรก เป็นจังหวัดที่มีความเสี่ยงน้ำท่วมสูง จึงสรุปได้ว่า ปัจจัยที่ทำในการนำท่วมอาจจะไม่ได้มีเพียงเเค่ปริมาณน้ำฝน อาจจะมีปัจจัยอื่นๆ ที่ส่งผลให้เกิดน้ำท่วม

# Challenge 
  1. การใช้ seaborn ในการ plot กราฟ ได้ภาพออกมาไม่ค่อยชัด และ กราฟไม่สามารถที่จะเลือกกด คลิ๊กๆ แล้วข้อมูลเปลี่ยนตามที่คลิ๊ก เช่น Plotly Express สามารถทำได้แล้วภาพคมชัดกว่า
  2.Dataset ที่เป็นภาษาไทยเมื่อใช้ seaborn plot กราฟ จะแสดงเป็นตัวหนังสือที่อ่านไม่ออก ต้องทำการ เพิ่ม font ก่อน จึงจะสามารถเเสดงเป็นภาษาไทยได้
  3. เนื่องจากข้อมูลที่มีค่อนข้างละเอียด แต่ด้วยระยะเวลาที่มี และความถนัดในการใช้เครื่องมือไม่เอื้ออำนวยจึงขุด insight ได้ไม่ลึกกว่านี้
 

# Solution 
เริ่มเเรก โดยการติดตั้ง Libraly เพื่อการพร้อมใช้งาน

![image](https://user-images.githubusercontent.com/105144684/196046984-71706adb-86aa-49c1-9f00-85d707508ec3.png)

โหลดข้อมูลเข้าตัวแปร DataFrame ของ Pandas โดยจะจัดเก็บข้อมูลในตัวแปรเป็นตาราง มีแถวและมีคอลัมน์ โดยจะโหลดข้อมูลทั้งหมด 3 ไฟล์ 
1. area-flood  คือไฟล์ข้อมูลปริมาณน้ำฝนเชิงพื่นที่
2. spatial-rain คือไฟล์ข้อมูลพื่นที่เสี่ยงน้ำท่วม
3. Province-Master คือไฟล์ข้อมูลจังหวัดและภูมิภาคในประเทศไทย

จากนั้นตรวจสอบข้อมูลที่เข้า โดยใช้ groupby เพื่อตรวจสอบชื่อจังหวัดว่าเขียนรูปแบบเดียวกันหรือไม่ เช่น จ.กำแพงเพชร/จังหวัดกำแพงเพชร/กำแพงเพชร และ df.inf() เพื่อตรวจสอบค่า na
จากการตรวจสอบพบว่าในไฟล์ area-flood มีชื่อจังหวัดที่เขียนรูปแบบไม่เหมือนกันอยู่ ดังนั้นจึงใช้รหัสจังหวัดเป็น key ในการ join ข้อมูลระหว่างไฟล์เพื่อนำชื่อจังหวัดจากไฟล์ Province-Master ไปใช้ รวมไปถึงนำข้อมูลภูมิภาคมาใช้ด้วย  เนื่องจากต้องการนำข้อมูลจากไฟล์ spatial-rain และ area-flood มารวมกัน เเต่ทั้ง 2 นี้มีรายเอียดลงถึงรายเดือน จึงต้องทำการสร้าง Key โดยการนำรหัสจังหวัด-เดือน เพื่อใช้ในการ join ข้อมูล
![image](https://user-images.githubusercontent.com/105144684/196047081-6c06a39b-6486-4986-893a-2c854984829e.png)
![image](https://user-images.githubusercontent.com/105144684/196047095-68ddd296-1e49-438d-96dc-b5ca6bee975f.png)
![image](https://user-images.githubusercontent.com/105144684/196047102-d809706e-6d0d-4dcd-ae3d-c688fb34b040.png)
![image](https://user-images.githubusercontent.com/105144684/196047115-50ed0694-ca62-41ec-96a2-e20ae6089580.png)
![image](https://user-images.githubusercontent.com/105144684/196047129-78250cd5-739c-426d-95fb-182d50aede6f.png)
![image](https://user-images.githubusercontent.com/105144684/196047141-b6eb2a22-9015-43d4-b750-a6594b7da0ea.png)

Rename ชื่อ column ให้เป็นภาษาไทยเพื่อให้เข้ากับ dataset เเละอ่านเข้าใจง่ายขึ้น 

![image](https://user-images.githubusercontent.com/105144684/196047159-7ee6f055-73b9-4c00-8a8e-be8f7e13d56f.png)

# Analysis

นำข้อมูลมาจัดทำกราฟ เพื่อแสดงเทรนของปริมาณน้ำฝนในประเทศไทย ตามเดือนในปี 2018-2022

![image](https://user-images.githubusercontent.com/105144684/196047200-51203873-1dd2-4c6c-a89d-0125f7f7be85.png)

จะพบว่า ฝนจะตกเยอะในช่วงเดือนสิงหาคม ถึงกันยายน เเละจะเริ่มลดลงมีฝนในช่วง เดือนมกราคม ถึงมีนาคม และเดือนตุลาคม ถึงธันวาคม
ในปี 2022 ตั้งแต่เดือนกุมภาพันธ์ ถึงกรกฎาคม ปริมาณน้ำฝนจะสูงกว่า 4 ปีย้อนหลัง ณ เดือนนั้นๆ ส่วนในเดือนสิงหาคม ปริมาณน้ำฝนจะสูงขึ้นมาจากปีที่เเล้ว

ดูรายละเอียดตามปี

![image](https://user-images.githubusercontent.com/105144684/196047288-498b1bca-3430-4831-8066-a21e71ab4174.png)
![output_13_2](https://user-images.githubusercontent.com/105144684/196047307-6e3e0dbb-3bd6-4236-9232-351f4cfc3c74.png)


นำข้อมูลมาจัดทำกราฟ เพื่อแสดงเทรนของปริมาณน้ำฝนในประเทศไทย ตามภูมิภาคในปี 2018-2022

![image](https://user-images.githubusercontent.com/105144684/196047576-47fa9078-1411-40cf-8d89-0bed11f8fd97.png)


จะพบว่า ภาคตะวันออกเฉียงเหนือจะมีปริมาณน้ำฝนมากที่สุด ในปี 2022 ภาคเหนือ ภาคกลาง และภาคตะวันออกเฉียงเหนือ ปริมาณน้ำฝนจะสูงกว่า 4 ปีย้อนหลัง ส่วนภาคใต้ปริมาณน้ำฝนจะลดลง

ดูรายละเอียดตามปี

![image](https://user-images.githubusercontent.com/105144684/196047590-0a56ed49-8f3f-47ea-a93a-9074734908b0.png)
![output_16_1](https://user-images.githubusercontent.com/105144684/196047602-6d94725f-0696-463c-98cc-7e7f9f3c00e9.png)

กรองข้อมูลเฉพาะปี 2022 

![image](https://user-images.githubusercontent.com/105144684/196047720-6a8455df-5189-4e26-932e-6f6f9e32275a.png)
![image](https://user-images.githubusercontent.com/105144684/196047732-8686fcc1-ffb3-4b82-98ac-67d4e9aed4a6.png)


นำข้อมูลมาจัดทำกราฟ เพื่อแสดงเทรนของปริมาณน้ำฝนในประเทศไทย ตามภูมิภาคในปี 2022

![image](https://user-images.githubusercontent.com/105144684/196047785-9531dcd3-5cd1-46e3-8733-5dc25281c09f.png)

เมื่อนำข้อมูลมากรองดูเฉพาะปี 2022 จะพบว่าภาคใต้ ภาคเหนือ และภาคกลางจะมีฝนตกอยู่ตลอดเริ่มตั้งเเต่ต้นปีจนถึงเดือนสิงหาคม ส่วนภาคตะวันออกเฉียงเหนือ จะเริ่มมีฝนในเดือนพฤษภาคม เป็นต้นมาเเละในเดือนสิงหาคม มีปริมาณน้ำฝนมากที่สุด

กรองข้อมูลเฉพาะปี 2022 เดือนสิงหาคม ซึ่งเป็นข้อมูลที่อัปเดตล่าสุด เพื่อนำมาวิเคราะห์ จังหวัดที่ปริมาณน้ำฝนมากๆ จะเป็นพื้นที่มีความเสี่ยงสูงที่จะเกิดน้ำท่วมหรือไม่

![image](https://user-images.githubusercontent.com/105144684/196047802-98e26453-810a-49e9-b507-cef06845fffe.png)


นำข้อมูลมาจัดทำกราฟ เพื่อแสดงเทรนของปริมาณน้ำฝนในประเทศไทย ตามภูมิภาคในปี 2022 เดือนสิงหาคม
จะพบว่า ภูมิภาคที่มีปริมาณน้ำฝนมากที่สุด คือ ภาคตะวันออกเฉียงเหนือ

![image](https://user-images.githubusercontent.com/105144684/196047819-c2160225-9a3b-4b66-9a9b-4b8efa21fe7d.png)


จะพบว่า เมื่อกรองข้อมูลเฉพาะปี 2022 เดือนสิงหาคม ภูมิภาคที่มีปริมาณน้ำฝนมากที่สุด ก็ยังคือ ภาคตะวันออกเฉียงเหนือ

คำนวณค่าสถิติของปริมาณน้ำฝนในปี 2022 เดือนสิงหาคม 

![image](https://user-images.githubusercontent.com/105144684/196047836-930de1f1-46e1-47c4-8381-892eec07107c.png)


นำข้อมูลมาจัดทำกราฟ เพื่อแสดงเทรน 10 อันดับแรกของปริมาณน้ำฝนในประเทศไทย ตามจังหวัดในปี 2022 เดือนสิงหาคม
จะพบว่า จังหวัดที่มีปริมาณน้ำฝนมากที่สุด คือ จังหวัดนครนายก 

![image](https://user-images.githubusercontent.com/105144684/196047845-5ec58652-df81-494d-8eaa-559bd9170bcd.png)
![output_22_1](https://user-images.githubusercontent.com/105144684/196047873-d44e30fb-8022-406e-9192-56da68834c83.png)

นำข้อมูลมาจัดทำกราฟ แสดงจำนวนตำบล ตามประเภทความเสี่ยง เพื่อดูสัดส่วนของความเสี่ยง

![image](https://user-images.githubusercontent.com/105144684/196047918-dc62fc77-8b4d-40be-b30e-daa662834dd0.png)
![image](https://user-images.githubusercontent.com/105144684/196047936-c8e30bf1-fbe8-4f14-a6cf-2a78e377661a.png)

จากนั้นกรองข้อมูลเฉพาะ ประเภทความเสี่ยงสูง  เพื่อนำมาดูว่าจังหวัดที่มีจำนวนตำบล ที่มีความเสี่ยงสูงที่จะเกิดน้ำท่วมมากที่สุด
จะพบว่า จังหวัดที่มีจำนวนตำบล ที่มีความเสี่ยงสูงที่จะเกิดน้ำท่วมมากที่สุด คือ จังหวัดสุโขทัย

![image](https://user-images.githubusercontent.com/105144684/196048026-1a13f7bf-4e2a-434a-8531-a1a071cbf43d.png)
![image](https://user-images.githubusercontent.com/105144684/196048036-4990c094-639f-4977-ac59-43b024b889b6.png)

นำข้อมูลพื้นที่ความเสี่ยงของจังหวัดสุโขทัย มาดูว่ามีอำเภอใดบ้างที่มีตำบลที่มีความเสี่ยงสูงและเป็นสัดส่วนเท่าใด

![image](https://user-images.githubusercontent.com/105144684/196048080-e5cdcfc7-0fae-43bf-8272-e62b0da1dcea.png)
![image](https://user-images.githubusercontent.com/105144684/196048147-20304973-0435-4faa-9f23-9b4aad55b5d6.png)
![image](https://user-images.githubusercontent.com/105144684/196048164-8be18eb5-88fd-4758-bbf7-485cf5aa43eb.png)
![image](https://user-images.githubusercontent.com/105144684/196048175-ffbe7285-6754-4d20-861f-0eac98933584.png)


# Conclusion

บทสรุป จากคำถามที่ว่า ในพื้นที่จังหวัดที่มีฝนตกปริมาณมากๆ จะมีความเสี่ยงสูงที่จะน้ำท่วมหรือไม่?
โดยจากการที่ได้นำข้อมูล ปริมาณน้ำฝนเชิงพื่นที่ และ ข้อมูลพื่นที่เสี่ยงน้ำท่วม จะพบว่า จังหวัดนครนายก ที่มีปริมาณน้ำฝนมากที่สุด ไม่ได้เป็นจังหวัดที่มีความเสี่ยงสูงที่จะน้ำท่วม เเต่ก็จะมีบางจังหวัด(จังหวัดหนองคาย จังหวัดนครพนม และจังหวัดบึงกาฬ)ที่มีปริมาณน้ำฝนอยู่ใน 10 อันดับแรก เป็นจังหวัดที่มีความเสี่ยงน้ำท่วมสูง ดังรูปด้านล่าง

![image](https://user-images.githubusercontent.com/105144684/195792519-12470625-30eb-4e99-a3d9-d80d9ace4e4f.png)

ดังนั้น จึงสรุปได้ว่า ปัจจัยที่ทำในการนำท่วมอาจจะไม่ได้มีเพียงเเค่ปริมาณน้ำฝน อาจจะมีปัจจัยอื่นๆ ที่ส่งผลให้เกิดน้ำท่วม เช่น  น้ำทะเลหนุนสูง พื้นที่เป็นแอ่งกระทะ  น้ำไหลจากภูเขา(น้ำป่า) ขยะมุลฝอยต่างๆ หรือการก่อสร้างถนนขวางทางน้ำ เป็นต้น
