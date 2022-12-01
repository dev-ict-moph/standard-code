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
| nationality_code | nationality_name_th | nationality_name_en |
| :--------: | :----------: | :----------: |
| 002          | โปรตุเกส          | PORTUGUESE         |

---


## สถานภาพสมรส -- marital_status.csv 

#### แหล่งมาตรฐานข้อมูล 

- [มหาดไทย](http://edw-opendata.moi.go.th/dataset/page/5efea934a63f8b7dc320999b9a314ce67d9691321b627)

##### ตัวอย่าง
| marital_status_code | marital_status_name_th | marital_status_name_en |
| :---------: | :------------: | :------------: |
| 1           | โสด            | Single         |
| 2           | สมรส           | Married        |

---
## อาชีพ -- occupations.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/1fu9ql1pjVfbKqmIJlM8ZZsCO5RsQfR0f/view)

##### ตัวอย่าง
| occupation_code | occupation_name_th | occupation_name_en |
| :-------------: | :----------------: | :----------------: |
| 0110            | ทหารชั้นสัญญาบัตร     |                   |
| 0210            | ทหารชั้นประทวน       |                   |

---
## ประเภทการวินิจฉัย -- diagnosis_types.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/open?id=1o7QU9sNAacfRPpKsG0S1zgVhLOLLdsTk)

##### ตัวอย่าง
| diagnosis_types_code | diagnosis_types_name_th | diagnosis_types_name_en |
| :------------------: | :---------------------: | :---------------------: |
| 1	                   | การวินิจฉัยโรคหลัก          | PRINCIPLE DX            |
| 2	                   | การวินิจฉัยโรคร่วม           | CO-MORBIDITY            |

---
## การวินิจฉัยโรคและอาการ (ICD10TM 2016) -- diagnosis.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/1gBnNQY8Tbw60rlAUY4IslDp31XQjGjms/view?usp=sharing)


##### ตัวอย่าง
| ICD10TM | diagnosis_name_th | diagnosis_name_en |
| :-----: | :------------------: | :------------------: |
| A000	  | อหิวาตกโรคจากเชื้อ วิบริโอ คอเลเรโอ 1 ไบอาวาร์ คอเลเร | Cholera due to Vibrio cholerae 01, biovar cholerae |
| A001	  | อหิวาตกโรคจากเชื้อ วิบริโอ คอเลเรโอ 1 ไบอาวาร์ เอลทอร์ | Cholera due to Vibrio cholerae 01, biovar eltor   |

---
## สิทธิการรักษาพยาบาล -- rights.csv  (*รอการจัด Group ใหม่)

#### แหล่งมาตรฐานข้อมูล 

- [สปสช.](https://www.nhso.go.th/downloads/64)
- [43แฟ้ม](https://drive.google.com/file/d/13HROCTleOTD6uq_Tk4AGG6eiqHzOAnVZ/view)

##### ตัวอย่าง
| rightsCode | rights_name_th |	rights_name_en |
| SSS | สิทธิประกันสังคม | Social Security Scheme |
| UCS |สิทธิหลักประกันสุขภาพ | Universal Coverage Scheme |

---
## สถานพยาบาล -- hosp_names.csv

#### แหล่งมาตรฐานข้อมูล 

- [กยผ.](http://203.157.10.8/hcode_2020/p_export.php)

##### ตัวอย่าง
| hosp_code |  hosp_name_th |  hosp_name_en | hosp_province_code | hosp_province_name_th | hosp_province_name_en | hosp_zone |
| :---------: | :----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: |
| 41866	      | คลินิกการแพทย์แผนไทยเตาปูน |        | 10 | กรุงเทพมหานคร | Bangkok | 13 |

---
## แผนกวินิจฉัย -- clinics.csv

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://docs.google.com/spreadsheets/d/1J7HWIyReeHArOmMdPPSok_HkUzNSiTZ-/edit#gid=1692007087)

##### ตัวอย่าง
| clinic_code_opd | clinic_code_ipd | clinic_name_th | clinic_name_en | 
| :-------------: | :-------------: | :------------: | :------------: |
| 00000	          | 10000           | หน่วยงานระดับสถานีอนามัยและศูนย์สุขภาพชุมชน |               | 
| 00100	          | 10100           |อายุรกรรม         |                | 

---
## ยา(43แฟ้ม) -- drugs_43_folders.csv

#### แหล่งมาตรฐานข้อมูล 

- [รหัสมาตรฐานยา43แฟ้ม](https://drive.google.com/file/d/1qMrhZAqnqH-8EMIHQqxuX5zCtY5bJqhP/view)


##### ตัวอย่าง
| drug_code | drug_24_code | active_ingredient | trade_name | manufacturer | FSN |	drug_type_code |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| | 100188000004293220181296 | TETRACYCLINE 250 MG CAPSULE	| ACNICIN T1 CAPSULE | บริษัท อาร์ พี ซี อินเตอร์เนชั่นแนล จำกัด | ACNICIN T1 CAPSULE(บริษัท อาร์ พี ซี อินเตอร์เนชั่นแนล จำกัด)(TETRACYCLINE 250 MG CAPSULE)() | 43folders |

---
## ยา(TMT) -- tmt_drugs.csv.csv

#### แหล่งมาตรฐานข้อมูล 

- [บัญชีข้อมูลยาและรหัสยามาตรฐานไทยสำหรับยาแผนไทย](https://www.this.or.th/service/ttmt/)

- [บัญชีข้อมูลยาและรหัสยามาตรฐานไทย(TMT)](https://www.this.or.th/service/tmt/download/)


##### ตัวอย่าง
| drug_code | drug_24_code | active_ingredient | strength | dosage_form	| content_value | content_unit| dispensing_unit | trade_name | manufacturer | FSN |	drug_type_code |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 9099264 | 420000000110000021510662 | กษัยเส้น |	|ยาลูกกลอน | |	| |	โรงพยาบาลชลบุรี | (โรงพยาบาลชลบุรี)(กษัยเส้น)()ยาลูกกลอน | TTMT |
| 105474 |                           | pantoprazole | 40 mg | gastro-resistant tablet |	 |  | tablet | CONTROLOC | ALTANA PHARMA, GERMANY |	CONTROLOC (ALTANA PHARMA, GERMANY) (pantoprazole 40 mg) gastro-resistant tablet, 1 tablet (TPU) | TMT |


