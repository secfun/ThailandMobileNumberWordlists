# ThailandMobileNumberWordlists
Thailand mobile phone number wordlists for bruteforce (etc. aircrack-ng , hydra , hashcat , more...)
ไฟล์ Wordlists เบอร์โทรศัพท์มือถือของประเทศไทย เลข 10 หลัก เพื่อใช้สำหรับทำ Bruteforce
ประกอบด้วย 3 ชุดคือเบอร์ที่ขึ้นต้นด้วย 06 , 08 , 09
แต่ละชุด มีจำนวน 100 ล้านเลขหมาย รวม 3 ชุด เป็น 300 ล้านเลขหมาย 

สำหรับ Hydra จะมีข้อจำกัด คือ Wordlists file ที่ใช้จะนับบรรทัดของรหัสผ่านที่ใช้ Bruteforce ซึ่ง Maximum ที่ 500,000 บรรทัดเท่านั้น
จึงทำการแบ่งไฟล์ออกเป็นไฟล์ย่อยๆ ไฟล์ละ 500,000 บรรทัด
ถ้าจะทำให้มัน automate Bruteforce ก็เขียน shell script for loop กับ hydra เอา ให้เปลี่ยนไฟล์ไปเรื่อยๆเมื่อยิงเสร็จแต่ละไฟล์ก็ได้

หรือใครสะดวกจะโหลดไฟล์ใหญ่ไฟล์เดียว 100 ล้านเลขหมาย ของแต่ละชุดสามารถดาวน์โหลดได้ ตามลิ้งด้านล่าง
#############################

Begin with : 0600000000 to 0699999999 (100,000,000 numbers)
Size of file = 1.1GB
https://mega.nz/file/N9lk1IQQ
SHA256(1.1GB-100MLine-ThaiMobileNumber06x)= 176f479bd20816a6d2020d16189d18c520b2ebf5a6d912c00fe2c6ae2c09f049




Begin with : 0800000000 to 0899999999 (100,000,000 numbers)
Size of file = 1.1GB
https://mega.nz/file/NxkAjQyL
SHA256(1.1GB-100MLine-ThaiMobileNumber08x)= 0a1d77981deefd1b2777f085888c8748a22d21be3191966e6d0c92a9110cfa74




Begin with : 0900000000 to 0999999999 (100,000,000 numbers)
Size of file = 1.1GB
https://mega.nz/file/0ltSSKaa
SHA256(1.1GB-100MLine-ThaiMobileNumber09x)= 7ebbfea7c96e85a199e0e5809eae787a432b70396f6d0a29edce0000fa4a2c6a

