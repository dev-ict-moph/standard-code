# Standard Code

การตั้งชื่อไฟล์และชื่อฟิลด์ อ้างอิงจาก MongoDB Naming Standards and Guidelines

- MongoDB Collection Naming => <mark>Lower case Example: account_record, credit_history</mark>


- [Links](https://www.thecodebuzz.com/mongo-db-naming-conventions-standards-guidelines/#aioseo-mongomongodb-naming-standards-and-guidelines---database-naming)

---
## คำนำหน้าชื่อ -- prefixes.csv 

#### แหล่งมาตรฐานข้อมูล 

- [มหาดไทย](http://edw-opendata.moi.go.th/dataset/page/5f11b90b2ef969d0f4f4594c10086ebe0229688d38c9d)

##### ตัวอย่าง
| prefix_code | prefix_name_th | prefix_name_en |
| :--------------: | :-----------------: | :-----------------: |
| 003	           | นาย	             | MR.                 |
| 004	           | นางสาว              | MISS                |

---
## หมู่เลือด -- blood_groups.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/1i9JC_r5LDbXqBZGGf1kyoRqR3E7CSUyW/view)

##### ตัวอย่าง
| blood_group_code | blood_group_name_th | blood_group_name_en |
| :--------------: | :-----------------: | :-----------------: |
| 1                | เอ                  | A                   |

---
## หมู่เลือดRH -- rh_blood_groups.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/11MkFMS-4cVaNTbBXQmjRJ8_VX82JoUyM/view)

##### ตัวอย่าง
| rh_blood_group_code | blood_group_name_th | blood_group_name_en |
| :-----------------: | :-----------------: | :-----------------: |
| 1                   |                     | Positive            |
| 2                   |                     | Negative            |

---
## เพศ -- genders.csv 

#### แหล่งมาตรฐานข้อมูล

- [มหาดไทย+](https://data.go.th/dataset/view_gender)

##### ตัวอย่าง
| gender_code | gender_name_th | gender_name_en |
| :--------: | :----------: | :----------: |
| 1          | ชาย          | Male         |

---
## สัญชาติ -- nationalities.csv 

#### แหล่งมาตรฐานข้อมูล

- [มหาดไทย](http://edw-opendata.moi.go.th/dataset/page/5f11bb7058296d0cd0a5609c9637cd33da403d6d02afa)

##### ตัวอย่าง
| NationalityCode | NationalityNameTh | NationalityNameEn |
| :--------: | :----------: | :----------: |
| 002          | โปรตุเกส          | PORTUGUESE         |

---


## สถานภาพสมรส -- marital_status.csv 

#### แหล่งมาตรฐานข้อมูล 

- [มหาดไทย](http://edw-opendata.moi.go.th/dataset/page/5efea934a63f8b7dc320999b9a314ce67d9691321b627)

##### ตัวอย่าง
| MaritalStatusCode | MaritalStatusNameTh | MaritalStatusNameEn |
| :---------: | :------------: | :------------: |
| 1           | โสด            | Single         |
| 2           | สมรส           | Married        |

---
## อาชีพ -- occupations.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/1fu9ql1pjVfbKqmIJlM8ZZsCO5RsQfR0f/view)

##### ตัวอย่าง
| OccupationCode | OccupationNameTh | OccupationNameEn |
| :---------: | :------------: | :------------: |
| 0110           | 	ทหารชั้นสัญญาบัตร            |          |
| 0210           | ทหารชั้นประทวน           |         |

---
## ประเภทการวินิจฉัย -- diagnosis_types.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/open?id=1o7QU9sNAacfRPpKsG0S1zgVhLOLLdsTk)

##### ตัวอย่าง
| DiagnosisTypesCode | DiagnosisTypesNameTh | DiagnosisTypesNameEn |
| :----------------: | :------------------: | :------------------: |
| 1	                 | การวินิจฉัยโรคหลัก       | PRINCIPLE DX         |
| 2	                 | การวินิจฉัยโรคร่วม        | CO-MORBIDITY         |

---
## การวินิจฉัยโรคและอาการ (ICD 10 TM) -- diagnosis.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/1gBnNQY8Tbw60rlAUY4IslDp31XQjGjms/view?usp=sharing)


##### ตัวอย่าง
| DiagnosisCode | DiagnosisNameTh | DiagnosisNameEn |
| :----------------: | :------------------: | :------------------: |
| A000	                 | อหิวาตกโรคจากเชื้อ วิบริโอ คอเลเรโอ 1 ไบอาวาร์ คอเลเร       | Cholera due to Vibrio cholerae 01, biovar cholerae         |
| A001	                 | อหิวาตกโรคจากเชื้อ วิบริโอ คอเลเรโอ 1 ไบอาวาร์ เอลทอร์        | Cholera due to Vibrio cholerae 01, biovar eltor         |

---
## สิทธิการรักษาพยาบาล -- rights.csv  (*รอการ Group ใหม่)

#### แหล่งมาตรฐานข้อมูล 

- [สปสช.](https://www.nhso.go.th/downloads/64)

##### ตัวอย่าง
| RightsCode |  RightsNameTh |  RightsNameEn  |
| :---------: | :----------: | :-----------: |
| SSS	      | สิทธิประกันสังคม | Social Security Scheme|

---
## สถานพยาบาล -- hosp_names.csv

#### แหล่งมาตรฐานข้อมูล 

- [กยผ.](http://203.157.10.8/hcode_2020/p_export.php)

##### ตัวอย่าง
| HospCode |  HospNameTh |  HospNameEn | HospProvinceCode | HospProvinceNameTh | HospProvinceNameEn | HospZone |
| :---------: | :----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: |
| 41866	      | | คลินิกการแพทย์แผนไทยเตาปูน | 10 | กรุงเทพมหานคร | Bangkok | 13 |

---
## แผนกวินิจฉัย -- main_departments.csv

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://docs.google.com/spreadsheets/d/1J7HWIyReeHArOmMdPPSok_HkUzNSiTZ-/edit#gid=1692007087)

##### ตัวอย่าง
| MainDepartmentCode |  MainDepartmentNameTh | MainDepartmentNameEn | 
| :---------: | :---------------: | :-----------: |
| 101	      | อายุรกรรม (ผู้ป่วยใน) |               | 
| 001	      | อายุรกรรม (ผู้ป่วยนอก) |              | 

---
## ยา(43แฟ้ม) -- forty_three_folders_drugs.csv

#### แหล่งมาตรฐานข้อมูล 

- [รหัสมาตรฐานยา43แฟ้ม](https://drive.google.com/file/d/1qMrhZAqnqH-8EMIHQqxuX5zCtY5bJqhP/view)

- ##### *รหัสยา24หลักไม่ซ้ำกับข้อมูลรหัสยามาตรฐานไทย(TMT)

- ##### *รอยืนยันรวมไฟล์ยา(43แฟ้ม)และยา(TMT)


##### ตัวอย่าง
| DrugCode |  DrugCode24 | DrugNameTh | DrugNameEn | DrugType |
| :------: | :---------------: | :-----------: | :-----------: |:-----------: |
| 	       | 213020100012320140681473 |           |  ANALGESIC BALM 30 %W/W OINTMENT | 43folders| 

---
## ยา(TMT) -- tmt_drugs.csv.csv

#### แหล่งมาตรฐานข้อมูล 

- [บัญชีข้อมูลยาและรหัสยามาตรฐานไทยสำหรับยาแผนไทย](https://www.this.or.th/service/ttmt/)

- [บัญชีข้อมูลยาและรหัสยามาตรฐานไทย(TMT)](https://www.this.or.th/service/tmt/download/)

- ##### *รหัสยา24หลักไม่ซ้ำกับข้อมูลยา(34แฟ้ม)

- ##### *รอยืนยันรวมไฟล์ยา(43แฟ้ม)และยา(TMT)


##### ตัวอย่าง
| DrugCode |  DrugCode24 | DrugNameTh | DrugNameEn | DrugType |
| :------: | :---------------: | :-----------: | :-----------: |:-----------: |
| 1049236 |  |           | 0.0001% DPCP (F 12249) (diphenylcyclopropenone 100 mcg/100 mL) cutaneous solution, 5 mL bottle (TPU) | TMT | 
| 9000002 | 410000000010000034110662 | กระเจี๊ยบแดง |  | TTMT | 

