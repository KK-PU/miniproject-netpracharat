# Net pracharat
Topic: ข้อมูลการใช้งาน อินเทอร์เน็ตประชารัฐ

Dataset: องค์กรสำนักงานปลัดกระทรวงดิจิทัลเพื่อเศรษฐกิจและสังคม
- https://data.go.th/dataset/village_internet_usage
- ข้อมูลการให้จุดติดตั้งอินเทอร์เน็ต 1 จุดต่อ 1 หมู่บ้าน จำนวนหมู่บ้านทั้วประเทศ 24,700 หมู่บ้าน
- ใช้ข้อมูล 3 เดือนย้อนหลัง (กันยายน,สิงหาคม,กรกฎาคม) ปี 2564
- ดึงข้อมูลจากไฟล์ csv 3 file (จำนวนแถวข้อมูลมี 24700 แถว)
- ไฟล์ข้อมูลที่รวมกันแล้วมีทั้งหมด (มี 74100 rows × 18 columns)

***สาเหตุที่ใช้ข้อมูลมาวิเคราะห์จำนวน 3 เพื่อต้องการเทียบค่าเฉลี่ยให้เห็น จากปริมาณการใช้งาน(ข้อมูลของภาครัฐ มีอัพเดตและเผยแพร่ ถึงแค่ปี พ.ศ. 2564) 

Question & Answer:

    คำถาม & คำตอบในการใช้ข้อมูลชุดนี้ :

     1. การใช้งานอินเทอร์เน็ต มีปริมาณการ UPLOAD,DOWNLOAD แต่ละเดือนเฉลียนมากน้อยหรือไม่ในการใช้งาน ?

        >> จากชุดข้อมูลการให้บริการโครงข่ายอินเทอร์เน็ตความเร็วสูงผ่านสื่อสัญญาณสายเคเบิลใยแก้วนำแสง (FTTx) ให้ครอบคลุมหมู่บ้านเป้าหมาย 

        จำนวน 24,700 หมู่บ้านที่ได้นำมาวิเคราะห์ ข้อมูลการใช้บริการอินเตอร์เน๊ตฟรี จากผลวิเคราะห์ข้อมูลคนไทยเข้าใช้บริการอินเตอร์เน๊ตเป็นจำนวน

        มากทั่วทั้งประเทศ จะเห็นได้ว่าความต้องการใช้อินเตอร์เน๊ตยังมีมากพอสมควรอยู่ คนไทยส่วนมากตามต่างจังหวัดหรือตามต่างอำเภอที่ห่างไกลจาก

        ตัวเมืองก็ยังมีคนที่เข้าไม่ถึงโครงข่ายอินเตอร์เน๊ตอยู่มาก ทำให้การมาใช้บริการอินเตอร์เน๊ตฟรีของภาครัฐจึงได้รับความสนใจในใช้บริการจำนวนมาก




    2. การที่รัฐให้บริการอินเทอร์เน็ต 1 จุดต่อ 1 หมู่บ้าน "แบบใช้ฟรี" ถือว่าจุดให้บริการพอสำหรับคนใช้งานในพื้นที่หรือไม่?

        >> จากชุดข้อมูลที่นำมาวิเคราะห์ ในงานใช้งานอินเตอร์เน๊ตอาจไม่เพียงพอต่อจำนวนผู้ใช้ของแต่ละหมู่บ้าน เพราะบ้างหมู่บ้านอาจจะมีจำนวน

        ประชากรที่อาศัยอยู่เยอะหรือน้อยแตกต่างกันไป ในการนำข้อมูลมาวิเคราะห์ทำให้เห็นว่าถ้าในอนาคตทางภาครัฐจะมีการนำข้อมูลการเก็บปริมาณสถิติ

        การใช้งานนเตอร์เน๊ตทั้งหมดนี้ไปทำการขยายจุดติดตั้งให้เพิ่มมากยิ่งขึ้น เพื่อที่ว่าจะได้เข้าถึงคนไทยที่ต้องการใช้งานอินเตอร์เน๊ตหรือคนไทยที่ยังไม่มี

        งบประมาณเพื่อลงทุนการซื้อใช้งานเองจากเจ้าบริการของเอกชน เพราะยังมีอีกหลายบ้านหลายคนที่ไม่มีโอกาสเข้าถึงได้..



    3. จากสถิติปริมาณการใช้งานอินเตอร์เน๊ตของคนไทย ในอนาคตทางภาครัฐจะมีโอกาสที่จะมีเพิ่มจุดบริการอินเทอร์เน็ต "ฟรี" ได้อีกหรือไม่ ? 

        >>  จากชุดข้อมูลถ้าในอนาคตภาครัฐ สามารถทำการขยายจุดติดตั้งการให้บริการอินเตอร์เน๊ตฟรี เพื่อบริการให้กับประชาชนไทยได้จำนวนมากขึ้น 

        นอกจาก 1 จุด 1 หมู่บ้านแล้ว อาจจะขยายไปตามวัด โรงเรียน หรือพื้นที่สาธารณะอื่นๆ เพิ่มเติมได้อีกหากมีโอกาสเป็นไปได้ เพื่อที่จะให้คนไทย

        ทุกๆคน ทุกๆที่เข้าถึงอินเตอร์เน๊ตเข้าถึงเทคโนโลยีได้ทุกที ตามเป้าหมายที่ภาครัฐได้วางเอาไว้ ในประเทศไทยก้าวทันโลก เด็กๆตามพื้นที่ห่างไกล

        สามารถก้าวทันเทคโนโลยีได้สะดวกรวดเร็ว ให้คนไทยตามที่ห่างไกลได้มีโอกาสพัฒนาคุณภาพชีวิตได้มากยิ่งขึ้น
        
        
        
 Challenge: ปัญหาที่เราพบและข้อสรุปการวิเคราะห์ข้อมูลชุดนี้
 
 -  ปัญหาที่พบ ข้อมูลจากแหล่งข้อมูลยังไม่ละเอียดพอที่จะทำให้วิเคราะห์ ลงไปลึกได้กว่านี้ หรือ วิเคราะห์ในรูปแบบที่หลักหลายกว่านี้

 -  คิดว่าบางจุดข้อมูลยังตั้งข้องสัยได้ไม่ค่อยละเอียดพอ ทำให้การวิเคราะห์ข้อมูลออกมาอาจจะยังไม่ละเอียดเท่าไรค่ะ
 
 -  ข้อมูลการนำ plot graph ก็ยังไม่สามารถทำแบบลงรายละเอียดลึกๆ ได้อีกค่ะเพราะข้อมูลยังไม่มากพอของข้อมูลที่เผยแพ่มาให้คะ



ในข้อมูลชุดนี้ที่ได้ทำการวิเคราะห์ คาดว่าจะได้เอาไปต่อยอดได้อีกในอนาคต จากการได้วิเคราะห์ชุดข้อมูลเพื่อได้เห็นปริมาณและความต้องการใช้งาน อินเทอร์เน็ตของคนไทยทั่วประเทศ หากว่าสถิติข้อูลชุดนี้มีการใช้งานอินเทอร์เน็ตเพิ่มขึ้นเรื่อยๆ ทางภาครัฐก็อาจจะมีโครงการขยายจุดให้บริการเพิ่มมากขึ้น เพื่อให้รองรับกับโครงการไทยแลนด์ 4.0 ตามเป้าหมายของภาครัฐและก็จะเป็นผลดีต่อคนไทยที่อยู่ห่างไกลจะได้เข้าถึงเทคโนโลยีก้าวทันโลกได้ง่ายขึ้น

    
